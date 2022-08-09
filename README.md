# Scripts

openmpi 4.1.4\
cuda 11.6.2 (with nvidia-driver 510.85.02)\
cudnn 8.4.1\
nccl2 2.12.12\
tensorflow 2.9.1\
pytorch 1.12.1\
horovod 0.25.0

horovodrun -np 3 -H localhost:3 python3 train_[tensorflow/pytorch]_mnist.py
