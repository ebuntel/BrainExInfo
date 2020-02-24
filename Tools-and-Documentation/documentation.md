---
title: BrainEx Documentation
---

[Main](https://ebuntel.github.io/BrainExInfo/) | [People](https://ebuntel.github.io/BrainExInfo/people/people) | [Publications](https://ebuntel.github.io/BrainExInfo/publications/publications) | Tools / Documentation

## Documentation

### How to install BrainEx on an AWS EC2 Instance

1. Install anaconda
2. Install Python3.7 ([Link](https://tecadmin.net/install-python-3-7-on-centos/))
3. Create a conda environment to run genex in:

'''
conda create -n myenv python=3.7
'''

4. Install genex requirements (ie: python -m pip install <PACKAGE>)
  
  * Numpy
  * Scipy
  * Cython
  * Tslearn
  * Pandas
  * Matplotlib
  * Pyspark
  
5. Install spark ([Link](https://gist.github.com/codspire/ee4a46ec054f962d9ef028b27fcb2635)) (Make sure to install JDK 8 first)
