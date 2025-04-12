# Pytorch-hebbian-renew-
This is a compliment for project: https://github.com/julestalloen/pytorch-hebbian?tab=readme-ov-file#about-the-project

由于使用的是3.8的Python才可以用的版本 我重新下载了一下Python3.8并且在上面重新部署了 以下是我的建议

1. 使用conda进行安装
   你需要在conda中新建一个虚拟环境 建议使用以下命令
```
# 创建新环境
conda create -n hebbian_env python=3.8 -y
conda activate hebbian_env

# 安装特定版本的 PyTorch
conda install pytorch=1.6.0 torchvision=0.7.0 cpuonly -c pytorch

# 安装 pytorch-hebbian
pip install git+https://github.com/Joxis/pytorch-hebbian.git
```

2. 如果使用VScode 记得使用Jupyter Notebook并且git整个程序到新建文件夹中
   我是保存在了 D:\Python project\Hebbian_learning\pytorch-hebbian-master\pytorch-hebbian-master 中，其中pytorch-hebbian-master\pytorch-hebbian-master 这部分是从git的zip文件直接解压得到的

   kernel选择新建的hebbian_env作为环境 并且将jupyter的文件保存在 D:\Python project\Hebbian_learning\pytorch-hebbian-master\pytorch-hebbian-master\pytorch_hebbian.ipynb
  
2（2）. 或者可以直接打开我的文件夹中的pytorch_hebbian.ipynb 开始评测

最后结果如下
Test Results - Loss: 0.9308 Accuracy: 0.7220
