# HOW-MUCH-POSITION-INFORMATION-DO-CONVOLUTIONAL-NEURAL-NETWORKS-ENCODE-
Reproduce the paper named 'HOW MUCH POSITION INFORMATION DO CONVOLUTIONAL NEURAL NETWORKS ENCODE?', which published as a conference paper at ICLR 2020.



ABSTRACT

In this review report, we introduce a different training dataset to reproduce the experiment. In the paper we chose, the authors built up with a simple Position En- coding Network (PosENet) to verify the hypothesis of how much and where the position information while offering clues about the positional information which derived from deep Convolutional Neural Networks (CNNs). Since the authors did not provide the source code, we used Pytorch successfully reproduced the vast majority of the experiment all by ourselves. And even some details did not be provided in the paper, we still restored the experiment through reasonable infer- ence. And the reproduced result in our experiment matches in general with the one from the original paper.



DATASET

DUTS Dataset: Training (images and ground-truth): http://saliencydetection.net/duts/download/DUTS-TR.zip

DUTS Dataset: Test (images and ground-truth): http://saliencydetection.net/duts/download/DUTS-TE.zip (this we used)



FILE EXPLAIN

images --> images for test

gt --> generated ground-truth

weights --> the weights of PosENet, VGG and Resnet model we generated
