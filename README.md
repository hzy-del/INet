# A Mural Image Inpainting Method Based on Nonlinear Perceptual Kernel and Adaptive Kernel Prediction

## Environment setup
- Python 3.7
- PyTorch >= 1.0 (test on PyTorch 1.0, 1.7.0)

conda create -n env python=3.7

conda activate env

conda install pytorch==1.7.0 torchvision==0.8.0 torchaudio==0.7.0 cudatoolkit=10.1 -c pytorch

pip install -r requirements.txt

## Train

python train.py
<br>
For the parameters: checkpoints/config.yml

## Test

python test.py

