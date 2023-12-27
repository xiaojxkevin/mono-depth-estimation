# Codes for CS172 Project

## Set up the environment
```bash
conda create -n depth python=3.8
conda activate depth 
conda install pytorch=1.10.0 torchvision=0.11.0 cudatoolkit=11.3 -c pytorch -c conda-forge
pip install opencv-python wandb scikit-image joblib
python -m pip install cityscapesscripts
pip install tensorboardX
conda install pytorch-sparse -c pyg
pip install chardet # https://blog.csdn.net/weixin_47037450/article/details/129616415
```