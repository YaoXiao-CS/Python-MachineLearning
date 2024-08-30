# Python-MachineLearning

此存储库用于同步存储书籍--[Machine Learning with PyTorch and Scikit-Learn](https://www.amazon.com/Machine-Learning-PyTorch-Scikit-Learn-scikit-learn-ebook-dp-B09NW48MR1/dp/B09NW48MR1/)相应章节的代码记录 。

This repository is used for synchronized storage of code records for the corresponding chapters of the book - [Machine Learning with PyTorch and Scikit-Learn](https://www.amazon.com/Machine-Learning-PyTorch-Scikit-Learn-scikit-learn-ebook-dp-B09NW48MR1/dp/B09NW48MR1/).

此存储库中的所有文件和代码脚本仅供学术用途。除此之外，请联系书籍[作者](https://x.com/rasbt)。

All files and code scripts in this repository are for academic use only. Beyond that, please contact the [author](https://x.com/rasbt) of this book.

---

# Conda Enviroment Installation Instructions

```
# 建议单独创建虚拟环境, <newName>是将要创建的环境名称，例如'mlbook'.
conda create --name newName python=3.7

# 激活新建的虚拟环境.
activate newName

# 查看已有的虚拟环境，选择要切换到的虚拟环境.
conda info --envs
# 或者
conda env list

# 在命令行中切换到上述创建的newName虚拟环境.
conda activate newName

# 便于在jupyter中切换使用，在当前环境中安装ipykernel.
conda install ipykernel

python -m ipykernel install --name newName

# 安装第三方工具包,进入到requirements.txt所在路径.
pip install -r requirements-ch01.txt
```
