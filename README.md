# MDD-Detection-with-EEG-Signals-using-a-Time-Series-Approach
This is a repository for our paper titled [Automated Detection of Major Depressive Disorder with EEG Signals: A Time Series Classification Using Deep Learning](https://ieeexplore.ieee.org/document/9828387) published in [IEEE Access](https://ieeexplore.ieee.org/document/9828387)
This study focuses on the automated detection of MDD using EEG data and deep neural network architecture. For this aim, first, a customized InceptionTime model is recruited to detect MDD individuals via 19-channel raw EEG signals. Then, a channel-selection strategy, which comprises three channel-selection steps,  is conducted to omit redundant channels.

The original InceptionTime paper also is available on [here](https://arxiv.org/pdf/1909.04939.pdf). 


## The proposed Inception network architecture 
![comgit](https://user-images.githubusercontent.com/96019816/162617323-416d4fec-b6ad-4a6e-afba-396e6b837392.jpg)

## Data
The data used in this project comes from the [MDD Patients and Healthy Controls EEG Data](https://figshare.com/articles/dataset/EEG_Data_New/4244171). 


## Requirements
You will need to install the following packages present in the [requirements.txt](https://github.com/AlirezaRafiei9/Detection-of-MDD-with-EEG-Signals-using-InceptionTIme-model/blob/master/requirements.txt) file. 

## Code
The code is divided as follows: 
* The [Inception classifier](https://https://github.com/AlirezaRafiei9/Detection-of-MDD-with-EEG-Signals-using-InceptionTIme-model/blob/main/Inception%20classifier) python file contains the Inception module python code using Keras library.
* The [Opening and sorting the files](https://https://github.com/AlirezaRafiei9/Detection-of-MDD-with-EEG-Signals-using-InceptionTIme-model/blob/main/Opening%20and%20sorting%20the%20files) python folder contains the steps of opening and labeling the files.
* The [Channel selection](https://https://github.com/AlirezaRafiei9/Detection-of-MDD-with-EEG-Signals-using-InceptionTIme-model/blob/main/Channel%20selection) python file involves general concepts of the channel selections approaches.


## Reference

If you are interested in this work, please cite:

```
@ARTICLE{9828387,
  author={Rafiei, Alireza and Zahedifar, Rasoul and Sitaula, Chiranjibi and Marzbanrad, Faezeh},
  journal={IEEE Access}, 
  title={Automated Detection of Major Depressive Disorder With EEG Signals: A Time Series Classification Using Deep Learning}, 
  year={2022},
  volume={10},
  number={},
  pages={73804-73817},
  doi={10.1109/ACCESS.2022.3190502}}
```
