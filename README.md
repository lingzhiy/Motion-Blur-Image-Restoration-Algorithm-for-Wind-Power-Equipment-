# Motion-Blur-Image-Restoration-Algorithm-for-Wind-Power-Equipment
Motion Blur Image Restoration Algorithm for Wind Power Equipment Based on Fourier Convolution and HBN Mechanism

For installing, follow these intructions
```
conda create -n pytorch python=3.8
conda activate pytorch
conda install pytorch==1.8.0 torchvision==0.9.0 torchaudio==0.8.0 
pip install -r requirements.txt
```

Install warmup scheduler

```
cd pytorch-gradual-warmup-lr; python setup.py install; cd ..
```

## Quick Run

```
python test.py 
```
Here is an example to train:
```
python train.py
```


## Reference Code:
- https://github.com/yangyanli/DO-Conv
- https://github.com/swz30/MPRNet
- https://github.com/chosj95/MIMO-UNet
- https://github.com/INVOKERer/DeepRFT


##Dataset links：
GoPro：https://drive.google.com/file/d/1KStHiZn5TNm2mo3OLZLjnRvd0vVFCI0W/view
DVD：https://drive.google.com/file/d/1bpj9pCcZR_6-AHb5aNnev5lILQbH8GMZ/view
NFS:https://drive.google.com/file/d/1Ut7qbQOrsTZCUJA_mJLptRMipD8sJzjy/view

