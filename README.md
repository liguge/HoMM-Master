# HoMM: Higher-order Moment Matching for Unsupervised Domain Adaptation

## HoMM-Master
<div align=center><img src="https://github.com/chenchao666/HoMM-Master/blob/master/img/img1.PNG" width="450" /></div>


* This repository contains code for our paper **HoMM: Higher-order Moment Matching for Unsupervised Domain Adaptation**
* If you have any question about our paper or code, please don't hesitate to contact with me ahucomputer@126.com, we will update our repository accordingly

## Setup
* **Dataset** The code as well as the dataset can be downloaded here [HoMM in MNIST](https://drive.google.com/open?id=167tVIBI2dVa0D18i6CiM-hicFJ3DJFzX) and [HoMM in Office&Office-Home](https://drive.google.com/open?id=1-OSkyh1Vzg_sxWJ6u4nvuQ3FRfKmZ-UF)

* **requirements** Python==2.7, tensorflow==1.9

## Training
* **MNIST** You can run **TrainLenet.py** in HoMM-mnist.
* **Office&Office-Home** You can run **finetune.py** in HoMM_office/resnet/.
* We have provide four functions **HoMM3**, **HoMM4**, **HoMM** and **KHoMM** conresponding to the third-order HoMM, fourth-order HoMM, Arbitrary-order moment matching, and Kernel HoMM.

## Reimplement HoMM in your work
Readers can reimplement the HoMM in their work very easily by using the following function.

**HoMM3**
