# hello-cuda-world

CUDA を用いて、２つの行列を加算するプログラム。

## 前提

```text
$ nvcc --version
nvcc: NVIDIA (R) Cuda compiler driver
Copyright (c) 2005-2018 NVIDIA Corporation
Built on Sun_Sep_30_21:09:22_CDT_2018
Cuda compilation tools, release 10.0, V10.0.166
```

## ビルドと実行方法

```text
$ make
$ obj/hello_cuda_world
Grid = (32, 32), Block = (32, 32)
A[00]=  4.3090, B[00]=  1.3820, G[00]=  5.6910
A[01]=  1.4590, B[01]=  1.7250, G[01]=  3.1840
A[02]=  6.5380, B[02]=  7.2470, G[02]= 13.7850
A[03]=  5.1050, B[03]=  9.6320, G[03]= 14.7370
A[04]=  0.3940, B[04]=  8.0170, G[04]=  8.4110
A[05]=  6.2570, B[05]=  5.5120, G[05]= 11.7690
A[06]=  4.4200, B[06]=  2.0190, G[06]=  6.4390
A[07]=  5.4830, B[07]=  8.9120, G[07]= 14.3950
A[08]=  3.2920, B[08]=  0.0180, G[08]=  3.3100
A[09]=  0.9000, B[09]=  2.5530, G[09]=  3.4530
Time elapsed 0.002759 sec (0.362438 GFLOPS)
```
