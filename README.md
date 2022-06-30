# Scripts

openmpi 4.1.4\
cuda 11.7.0 (with nvidia-driver 515.43.04)\
cudnn 8.4.1\
nccl2 2.12.12\
tensorflow 2.9.1\
pytorch \
horovod 0.25.0

horovodrun -np 3 -H localhost:3 python3 train_[tensorflow/pytorch]_mnist.py

tensorflow OK

pytorch FAIL

NVIDIA RTX A5000 with CUDA capability sm_86 is not compatible with the current PyTorch installation.\
The current PyTorch install supports CUDA capabilities sm_37 sm_50 sm_60 sm_70.\
If you want to use the NVIDIA RTX A5000 GPU with PyTorch, please check the instructions at https://pytorch.org/get-started/locally/
