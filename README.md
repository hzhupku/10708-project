## CFG-GAN 

**Requirements**  
* Python 3.6
* Tested with pyTorch 1.2.0 and torchvision 0.4.0. 
* pip install -r requirements.txt

**Training** 


* Train on MNIST

        python3 train_cfggan.py --dataset MNIST
        
* Train on LSUN

  Download the LSUN bedroom data as instructed at [https://github.com/fyu/lsun](https://github.com/fyu/lsun).

        python3 train_cfggan.py --dataset lsun_bedroom64 --dataroot lsun-root

        python train_cfggan.py --dataset lsun_church_outdoor64 --dataroot lsun-root
               
                     

