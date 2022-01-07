# SGUIE-Net: Semantic Attention Guided Underwater Image Enhancement with Multi-Scale Perception
This repository is the official PyTorch implementation of SGUIE-Net.
## Dataset preparation 
You need to prepare datasets for following training and testing activities, the detailed information is at [Dataset Setup](data/README.md).

## Train
``` 
python train.py --dataroot /path_to_data --name train_name --model SGUIENet --display_env display_env_name
```
## Test
```
python test.py --dataroot /path_to_data --name test_name --model test_SGUIE 
```
You can download the trained model from [here](https://drive.google.com/file/d/1vbY4GZ5-AwVKouDFHvFj9nL-grnIB2d3/view?usp=sharing).

## Citation

## Acknowledgements
- https://github.com/xahidbuffon/SUIM
- https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix