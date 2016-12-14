
**bv** is a small tool to quickly view high-resolution multi-band imagery directly in your terminal. It was designed for visualising very large images located on a remote machine over a low-bandwidth connection. 

<img src="https://github.com/daleroberts/tv/blob/master/docs/trump.png" width="800">

# Installation

It is just a single-file script so all you'll need to do it put it in your `PATH`.

Dependencies are Python 3, GDAL 2+, Numpy, and iTerm 2. I've found that the best way to install these dependencies are:
```bash
# Python 3
brew install python3

# Numpy
pip3 install numpy

# GDAL 2+
brew install gdal --HEAD --without-python
pip3 install gdal
```
