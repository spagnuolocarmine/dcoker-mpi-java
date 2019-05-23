# Docker image Ubuntu 18.04 OpenMPI 

This project provides a Docker container for an HPC environment based on OpenMPI, OpenMP, and Ubuntu Linux.

## Softwares

- Ubuntu 18.04
- bzip2 
- cmake 
- cpio 
- curl
- g++ 
- gcc 
- gfortran
- git 
- gosu
- libblas-dev 
- liblapack-dev 
- openmpi-bin 
- python3-dev 
- python3-pip 
- virtualenv 
- wget 
- zlib1g-dev 
- vim (preconfigured)
- htop
- java OpenJDK 1.8
- openmpi 4.0 wiht Java Bidiing enabled

## Use Docker Container

```docker build --no-cache -t dockermpi .```

```docker run -it -t dockermpi:latest ```

