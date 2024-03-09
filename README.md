# installing-notes

## GROMACS

`cmake ..  -DGMX_MPI=on -DGMX_FFT_LIBRARY=mkl -DGMX_GPU=CUDA -DMPI_CXX_COMPILER=mpicxx`

## nvidia-driver

Ref: https://blog.csdn.net/huiyoooo/article/details/128015155

## swich gdm3 to lightdm

```
sudo apt install lightdm
sudo dpkg-reconfigure gdm3
```
