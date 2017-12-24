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

Below are the results broken down by super category.

| Super Category |	Num Classes	| VGG-16 D.O | VGG-16 B.O | Inception-v3 D.O | Inception-v3 B.O |
|------|---------------|-------------|--------|----------|---------|-------|
Plantae|2,101|72.31 | 71.28 | 85.96 | 82.13 |
Insecta|1,021|74.44|72.14|89.66|85.22|
Aves|964|75.19|71.53|85.40|81.92|
Reptilia|289|71.11|62.34|74.56|65.41|
Mammalia|186|76.90|65.31|79.48|64.58|
Fungi|121|76.41|62.15|89.44|75.77|
Amphibia|115|78.25|59.13|75.09|61.23|
Mollusca|93|81.00|59.43|83.00|68.52|
Animalia|77|72.14|52.34|85.39|66.21|
Arachnida|56|70.15|57.21|88.95|56.72|
Actinopterygii|53|74.51|43.24|79.90|55.23|
Chromista|9|73.55|41.23|81.94|43.12|
Protozoa|4|74.25|31.67|91.78|51.23|


