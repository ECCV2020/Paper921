# Discretization-aware Architecture Search
Code accompanying the paper


README is being modified, please look at code first


## Requirements
```
Python >= 3.5.5, PyTorch == 0.4
```

## Datasets
We used CIFAR-10 and Imagenet dataset in this paper. CIFAR-10 can be automatically downloaded by torchvision, ImageNet needs to be manually downloaded following the instructions [here](https://github.com/pytorch/examples/tree/master/imagenet).


## Architecture evaluation (using full-sized models)
To evaluate our best cells by training from scratch, run
```
cd cnn && python train.py --auxiliary --cutout            # CIFAR-10
cd cnn && python train_imagenet.py --auxiliary            # ImageNet
```
# Paper921
