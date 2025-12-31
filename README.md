# **Overview**
<div align="center">
<img width="834" height="548" alt="cd32efdff0bc3c44ccd97ca3ba1c2489" src="https://github.com/user-attachments/assets/cc4b50bb-88b5-4970-a5ed-6a33cd90dbe0" />
</div>

Fig. 1. Overview of the proposed progressive Mamba GAN. The longitudinal progression learning stage models normative and pathological trajectories from sequential paired PET images. During cross-sectional assessment stage, image representations are extracted from the generated follow-up images.

# **Installation**<br />
requirements:<br />
Linux<br />
NVIDIA GPU<br />
PyTorch 1.12+<br />
CUDA 11.6+<br />

mamba create -n myenv python=3.10 numpy pandas -c conda-forge<br />
conda activate myenv<br />
git clone https://github.com/state-spaces/mamba.git<br />
cd mamba<br />
pip install -e<br />
