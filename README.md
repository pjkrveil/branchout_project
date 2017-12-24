# Fitting BranchOut Regularization for Object Recongnition

### Training
The network was trained on

- OS : Ubuntu 16.04 LTS
- GPU : Nvidia Tesla K40M
- Framework : PyTorch 0.1.12.

The links for the raw data are available [here](https://github.com/visipedia/inat_comp).

We also provide a pretrained model that can be downloaded from [here](https://www.dropbox.com/s/8ooqdnikmcx4eee/inception_v3_best.pth.tar?dl=0)

### Results
The VGG-16 architecture with BranchOut for about 32 epochs results in a Top-1 accuracy of 23.64% and Top-5 of 69.24% on the validation set, while the architecture with DropOut for same conditions results in a Top-1 accuracy of 56.44% and Top-5 of 73.77% on the validation set.
