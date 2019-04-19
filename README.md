# Sniffer-Net
<p align="left">
		<img src="https://img.shields.io/badge/version-0.1-brightgreen.svg?style=flat-square"
			 alt="Version">
		<img src="https://img.shields.io/badge/status-Release-gold.svg?style=flat-square"
			 alt="Status">
		<img src="https://img.shields.io/badge/platform-linux16.04-lightgrey.svg?style=flat-square"
			 alt="Platform">
		<img src="https://img.shields.io/badge/PyTorch version-1.0-blue.svg?style=flat-square"
			 alt="PyTorch">
		<img src="https://img.shields.io/badge/License-MIT License-green.svg?style=flat-square"
			 alt="License">
</p>
	A unified network structure  specialized for smoke detection and concentration evaluation in the wild.<b>
	
## Demo
This is a demo of our Sniffer-Net (including smoke detection, optical flow inpainting, smoke concentration evaluation).<b>
  
![image](https://github.com/namemzy/Sniffer-Net/blob/master/img/sniffer-net_demo.png)

## Several smoke datasets

Institution  | Website| Size| Quantity|
--------- | --------| --------- | --------|
Italy Modena University  | http://imagelab.ing.unimore.it/visor/ | /  | / |
Keimyung University  | http://cvpr.kmu.ac.kr/ | 320x240 video  | 38 |
University of Bilkent  | http://signal.ee.bilkent.edu.tr/visifire/ | 720x576 video  | 4 |
University of Split  | http://wildfire.fesb.hr/index.php | 720x576 video  | 5 |
University of Salerno  | https://mivia.unisa.it/ | multi-resolution video  | 149 |
University of Milan  | http://homes.di.unimi.it/genovese/wild/wildfire.htm | 320x240 video  | 20 |
FIRESENSE  | http://doi.org/10.5281/zenodo.836749 | multi-resolution video  | 49 |
USTC smoke dataset | http://smoke.ustc.edu.cn/| 1920x1080 video  | >30 |
Ours(Sniffer-Net) | https://github.com/namemzy/Sniffer-Net| 1920x1080 video  | 30 |

Foreign Websites Download slowly. We have downloaded them and put them on [Baidu Yunpan](https://pan.baidu.com/s/11uJgfiKI8_Ew2eG-h7sF4A).<b>
  
The dataset is available on:
### image pairs
https://pan.baidu.com/s/1dJS7aKZKILOK5LffN1nu4Q
### videos
https://pan.baidu.com/s/1BDkt2sEjZI5gRH5NZaJflw
### Some other datasets：
https://pan.baidu.com/s/11uJgfiKI8_Ew2eG-h7sF4A
### fisheye lens images
https://pan.baidu.com/s/1woqMBD7qwQMciccOpmU2CQ
  
## Implementation
### Prerequisites
- Ubuntu 16.04
- Pytorch 1.0
- CUDA 8.0 and cuDNN 5.1
- opencv3<b>
	
### <span id='ins'>Installation</span>
- Clone this repo
- Install PyTorch and dependencies from http://pytorch.org


## MIT License
Copyright (c) `2019 namemzy`
### Citation

If you find this project useful for your research, please cite:

```
@{smoke detection project,
author = {namemzy},
title = {Sniffer-Net},
website = {https://github.com/namemzy/Sniffer-Net},
month = {April},
year = {2019}
}
```
