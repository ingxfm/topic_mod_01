# topic_mod_01

## Install OpenBLAS on Linux:
``` Linux
$ sudo apt update
$ apt search openblas
$ sudo apt install libopenblas-dev
```
Then:
``` Linux
$ sudo update-alternatives --config libblas.so.3
```
Or:
``` Linux
sudo update-alternatives --remove  libblas.so.3 /usr/lib/x86_64-linux-gnu/libopenblas.so.0
```

## Install SciPy and NumPy
Go to your Python environment:
``` Linux
pip install scipy
pip install numpy
```

## Install gensim

``` Linux
pip install --upgrade gensim
```

# References:
- https://github.com/xianyi/OpenBLAS/wiki/Precompiled-installation-packages
- https://pypi.org/project/gensim/
