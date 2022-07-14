# LabelMe

**说明**：本篇笔记仅作为学习参考，用于作者个人学习记录和分享。

- [LabelMe](#labelme)
  - [Prepare work](#prepare-work)
  - [Installation](#installation)
    - [Ubuntu](#ubuntu)
    - [Windows](#windows)
  - [Usage](#usage)
  - [FQA](#fqa)
  - [References](#references)


## Prepare work
- Ubuntu / Windows
- Anaconda

## Installation
### Ubuntu
```
# Create a anaconda environment.
conda create -n labelme python=3.8
conda activate labelme

# Install dependency package.
pip install labelme
# In China, you maybe feel installation speed is slow, and you can try this command.
pip install labelme -i https://pypi.tuna.tsinghua.edu.cn/simple some-package
```

### Windows
```
# Create a anaconda environment.
conda create -n labelme python=3.8
conda activate labelme

# Install dependency package.
pip install labelme
# In China, you maybe feel installation speed is slow, and you can try this command.
pip install labelme -i https://pypi.tuna.tsinghua.edu.cn/simple some-package
```


## Usage

```
# Open the labelme application
# but this command is nothing files on labelme view, You had manual input your various File.
labelme

# You can run labelme on already have dataset, and revise it.

```






## FQA
1. At July 15, 2022, I use the labelme on python 3.8, because I run the labelme that appeared error on another versions.


## References
https://github.com/wkentaro/labelme.git.
