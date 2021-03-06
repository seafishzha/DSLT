
# Deep Regression Tracking with Shrinkage Loss

### Introduction

This is the research code for the ECCV 2018 paper: 

[Xiankai Lu](https://github.com/carrierlxk),  [Chao Ma](https://sites.google.com/site/chaoma99/), [Bingbing Ni](https://scholar.google.com/citations?user=eUbmKwYAAAAJ&hl=en), [Xiaokang Yang](http://english.seiee.sjtu.edu.cn/english/detail/842_802.htm), [Ian Reid](https://cs.adelaide.edu.au/~ianr/), and [Ming-Hsuan Yang](http://faculty.ucmerced.edu/mhyang/), " Deep Regression Tracking with Shrinkage Loss", ECCV 2018. 


<img src="https://sites.google.com/site/chaoma99/home/eccv18_dslt.png" width="800" />


### Abstract
Regression trackers directly learn a mapping from regularly dense samples of target objects to soft labels, which are usually generated by a Gaussian function, to estimate target positions. Due to the potential for fast-tracking and easy implementation, regression trackers have received increasing attention recently. However, state-of-the-art deep regression trackers do not perform as well as discriminative correlation filters (DCFs) trackers. We identify the main bottleneck of training regression networks as extreme foreground-background data imbalance. To balance training data, we propose a novel shrinkage loss to penalize the importance of easy training data.  Additionally, we apply residual connections to fuse multiple convolutional layers as well as their output response maps. Without bells and whistles, the proposed deep regression tracking method performs favorably against state-of-the-art trackers, especially in comparison with DCFs trackers, on five benchmark datasets including OTB-2013, OTB-2015, Temple-128, UAV-123 and VOT-2016.


### Citation

If you find the code and dataset useful in your research, please consider citing:


    @inproceedings{Lu-ECCV-2018,
        title={Deep Regression Tracking with Shrinkage Loss},
        Author = {Lu, Xiankai and Ma, Chao and Ni, Bingbing and Yang, Xiaokang and Reid, Ian and Yang, Ming-Hsuan},
        booktitle = {Proceedings of the European Conference on Computer Vision},
        pages={},
        Year = {2018}
    }

### Contents
|  Folder    | description |
| ---|---|

Feedbacks and comments are welcome! Feel free to contact us via [carrierlxk@gmail.com](mailto:carrierlxk@gmail.com) or [chaoma99@gmail.com](mailto:chaoma99@gmail.com).

Enjoy!
