# SRCNet-Recurrent Convolutional Neural Networks for AMR Steganalysis Based on Pulse Position

##  说明

​        现有固定码本自适应隐写算法可以有效抵抗隐写分析的攻击。我们以RNN和CNN构建固定码本的隐写分析网络，以脉冲位置作为网络的输入，该网络取得了较好的攻击性能。 网络结构参考下图。

![image](https://github.com/gongchenIH/Pic/blob/master/SRCNet.png)

[[paper]](https://dl.acm.org/doi/abs/10.1145/3335203.3335708)[[code]](https://github.com/gongchenIH/Speech-Steganography-in-Compressed-Domian/blob/main/2-Steganalysis/2.2-FCB_Steganalysis/Python/SRCNet.py)

## 参考论文

#### 1. [隐写算法](https://github.com/gongchenIH/Speech-Steganography-in-Compressed-Domian/tree/main/1-Steganography/1.1.1-PD_Steganpgraphy_Embed_byte)

- **Geiser**: Bernd Geiser and Peter Vary. 2008. [High rate data hiding in ACELP speech codecs](https://ieeexplore.ieee.org/document/4518532). In Acoustics, Speech and Signal Processing, 2008. ICASSP 2008. IEEE International Conference on. IEEE, 4005–4008
- **Miao**: Haibo Miao, Liusheng Huang, Zhili Chen, Wei Yang, and Ammar Al-Hawbani. 2012. [A new scheme for covert communication via 3G encoded speech](https://www.sciencedirect.com/science/article/abs/pii/S0045790612000900). Computers & Electrical Engineering 38, 6 (2012), 1490–1501.

- **AFA**: Yanzhen Ren, Hongxia Wu, and Lina Wang. 2018. [An AMR adaptive steganography algorithm based on minimizing distortion](https://link.springer.com/article/10.1007/s11042-017-4860-1). Multimedia Tools and Applications 77, 10 (2018), 12095–12110.


#### 2. [隐写分析算法](https://github.com/gongchenIH/Speech-Steganography-in-Compressed-Domian/tree/main/2-Steganalysis/2.3-PD_Steganalysis)

- **Fast-SPP**: Yanzhen Ren, Tingting Cai, Ming Tang, and Lina Wang. 2015. [AMR steganalysis based on the probability of same pulse position](https://ieeexplore.ieee.org/document/7083709). IEEE Transactions on Information Forensics and Security 10, 9 (2015), 1801–1811.
- **MTJCE**:  Haibo Miao, Liusheng Huang, Yao Shen, Xiaorong Lu, and Zhili Chen. 2013. [Steganalysis of compressed speech based on Markov and entropy](http://www.springer.com/cda/content/document/cda_downloaddocument/9783662438855-t1.pdf?SGWID=0-0-45-1466561-p176805394). In International Workshop on Digital Watermarking. Springer, 63–76.

# SRCNet-Recurrent Convolutional Neural Networks for AMR Steganalysis Based on Pulse Position

## Abstract

​    With the rapid development of stream multimedia, the adaptive multi-rate (AMR) audio steganography are emerging recently. However, the traditional steganalysis methods face great challenges in detecting short time speech at low embedding rates. To address this problem, we propose a steganalytic scheme by combining Recurrent Neural Network (RNN) and Convolutional Neural Network (CNN), SRCNet. AMR fixed codebook (FCB) steganography embed messages by modifying the pulse positions, which would destroy the FCB correlation. Firstly we analyzed the FCB correlations at different distances, and summarized these correlations into four categories. Furthermore, we utilizes RNN to extract higher level contextual representations of FCBs and CNN to fuse spatial-temporal features for the steganalysis. The proposed approach was evaluated on a public data-set. The experiment results validate that the proposed framework greatly outperforms the existing state-of-the-art methods. The correct detection rate of SRCNet has been improved above at least 10% when the sample is as short as 100ms at the 20% embedding rate. In particular, the network achieves the significant improvements for detecting the STCs based adaptive AMR steganography.

## Reference paper

#### 1. [Steganography](https://github.com/gongchenIH/Speech-Steganography-in-Compressed-Domian/tree/main/1-Steganography/1.1.1-PD_Steganpgraphy_Embed_byte)

- **Geiser**: Bernd Geiser and Peter Vary. 2008. [High rate data hiding in ACELP speech codecs](https://ieeexplore.ieee.org/document/4518532). In Acoustics, Speech and Signal Processing, 2008. ICASSP 2008. IEEE International Conference on. IEEE, 4005–4008
- **Miao**: Haibo Miao, Liusheng Huang, Zhili Chen, Wei Yang, and Ammar Al-Hawbani. 2012. [A new scheme for covert communication via 3G encoded speech](https://www.sciencedirect.com/science/article/abs/pii/S0045790612000900). Computers & Electrical Engineering 38, 6 (2012), 1490–1501.

- **AFA**: Yanzhen Ren, Hongxia Wu, and Lina Wang. 2018. [An AMR adaptive steganography algorithm based on minimizing distortion](https://link.springer.com/article/10.1007/s11042-017-4860-1). Multimedia Tools and Applications 77, 10 (2018), 12095–12110.


#### 2. [Stgeganalysis](https://github.com/gongchenIH/Speech-Steganography-in-Compressed-Domian/tree/main/2-Steganalysis/2.3-PD_Steganalysis)

- **Fast-SPP**: Yanzhen Ren, Tingting Cai, Ming Tang, and Lina Wang. 2015. [AMR steganalysis based on the probability of same pulse position](https://ieeexplore.ieee.org/document/7083709). IEEE Transactions on Information Forensics and Security 10, 9 (2015), 1801–1811.
- **MTJCE**:  Haibo Miao, Liusheng Huang, Yao Shen, Xiaorong Lu, and Zhili Chen. 2013. [Steganalysis of compressed speech based on Markov and entropy](http://www.springer.com/cda/content/document/cda_downloaddocument/9783662438855-t1.pdf?SGWID=0-0-45-1466561-p176805394). In International Workshop on Digital Watermarking. Springer, 63–76.

