# Install R 4.4.0 by Spack

```bash
## Spack 默认用已有的依赖快速安装
## --fresh可以全新安装，避免依赖是由旧版本编译器引起的兼容问题
spack install -j 8 --fresh r@4.4.0 %gcc@13.2.0
```

# R依赖的库
## 以Ubunut 22.04为例
```bash
sudo apt install gfortran
sudo apt install cmake
sudo apt install -y curl
sudo apt install -y libcurl4-gnutls-dev
sudo apt install -y libxml2-dev
sudo apt install -y libssl-dev
sudo apt install -y libmariadb-dev
sudo apt install -y libcurl4-openssl-dev
sudo apt install -y libgsl0ldbl
sudo apt install -y gsl-bin libgsl0-dev
sudo apt install -y build-essential
sudo apt install -y liblapack-dev libopenblas-dev
sudo apt install -y libfontconfig1-dev
sudo apt install -y libblas-dev
sudo apt install -y zlib1g-dev
sudo apt install -y libboost-all-dev
sudo apt install -y libbz2-dev
sudo apt install -y liblzma-dev
sudo apt install -y libudunits2-dev
sudo apt install -y libjpeg-dev
sudo apt install -y libgdal-dev gdal-bin libproj-dev proj-data proj-bin libgeos-dev
```
