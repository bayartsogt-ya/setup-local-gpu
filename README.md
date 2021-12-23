# setup-local-gpu
When I format my PC, seems like I am repeating the same thing over and over again.

## Install CUDA 11.0
Good practice https://www.tensorflow.org/install/gpu#ubuntu_1804_cuda_110

## Install necessary packages
```
pip install -r requirements.txt
```


## NVTOP

Deps:
```
sudo apt install cmake libncurses5-dev libncursesw5-dev git
```

Nvtop 
```
git clone https://github.com/Syllo/nvtop.git
mkdir -p nvtop/build && cd nvtop/build
cmake ..
make

# Install globally on the system
sudo make install
```
