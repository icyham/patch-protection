# adv-patch
PyTorch implementation of adversarial patch 

This is an implementation of the <a href="https://arxiv.org/pdf/1712.09665.pdf">Adversarial Patch paper</a>. And implementation of custom protection system.

## ImageNetSet:

In order for this to work you need to manually download ImageNet set:

 - Sign up and follow instructions from http://image-net.org/download-images.
 
## MishCuda

And install mish activation function for cuda

```
git clone https://github.com/JunnYu/mish-cuda
cd mish-cuda
python setup.py build install
```

## Usage

After that you can:

 - Train your patches with patch.ipynb

 - Create your dataset with dataset_creation.ipynb

 - Train your detection neural network with train.py

 - Test the protection system with test.ipynb