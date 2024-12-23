# Python-Machine Learning

此存储库用于同步存储书籍--[Machine Learning with PyTorch and Scikit-Learn](https://www.amazon.com/Machine-Learning-PyTorch-Scikit-Learn-scikit-learn-ebook-dp-B09NW48MR1/dp/B09NW48MR1/)相应章节的代码记录 。

This repository is used for synchronized storage of code records for the corresponding chapters of the book - [Machine Learning with PyTorch and Scikit-Learn](https://www.amazon.com/Machine-Learning-PyTorch-Scikit-Learn-scikit-learn-ebook-dp-B09NW48MR1/dp/B09NW48MR1/).

此存储库中的所有文件和代码脚本仅供学术用途。除此之外，请联系书籍作者[Sebastian Raschka](https://x.com/rasbt)。

All files and code scripts in this repository are for academic use only. Beyond that, please contact the [author](https://x.com/rasbt) of this book.

```
@book{mlbook2022,  
address = {Birmingham, UK},  
author = {Sebastian Raschka, and Yuxi (Hayden) Liu, and Vahid Mirjalili},  
isbn = {978-1801819312},   
publisher = {Packt Publishing},  
title = {{Machine Learning with PyTorch and Scikit-Learn}},  
year = {2022}  
}
```

---

# Conda Enviroment Installation Instructions

```
# 建议单独创建虚拟环境, <newName>是将要创建的环境名称，例如'mlbook'.
conda create --name newName python=3.9

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

---

# Table of Contents and Jupyter Notebooks

1. [Machine Learning - Giving Computers the Ability to Learn from Data.](https://nbviewer.jupyter.org/urls/raw.githubusercontent.com/YaoXiao-CS/Python-MachineLearning/main/Chapter-01.ipynb)
2. [Training Machine Learning Algorithms for Classification.](https://nbviewer.jupyter.org/urls/raw.githubusercontent.com/YaoXiao-CS/Python-MachineLearning/main/Chapter-02.ipynb)
3. [A Tour of Machine Learning Classifiers Using Scikit-Learn.](https://nbviewer.jupyter.org/urls/raw.githubusercontent.com/YaoXiao-CS/Python-MachineLearning/main/Chapter-03.ipynb)
4. [Building Good Training Sets – Data Pre-Processing.](https://nbviewer.jupyter.org/urls/raw.githubusercontent.com/YaoXiao-CS/Python-MachineLearning/main/Chapter-04.ipynb)
5. [Compressing Data via Dimensionality Reduction.](https://nbviewer.jupyter.org/urls/raw.githubusercontent.com/YaoXiao-CS/Python-MachineLearning/main/Chapter-05.ipynb)
6. [Learning Best Practices for Model Evaluation and Hyperparameter Optimization.](https://nbviewer.jupyter.org/urls/raw.githubusercontent.com/YaoXiao-CS/Python-MachineLearning/main/Chapter-06.ipynb)
7. [Combining Different Models for Ensemble Learning.](https://nbviewer.jupyter.org/urls/raw.githubusercontent.com/YaoXiao-CS/Python-MachineLearning/main/Chapter-07.ipynb)
8. [Applying Machine Learning to Sentiment Analysis.](https://nbviewer.jupyter.org/urls/raw.githubusercontent.com/YaoXiao-CS/Python-MachineLearning/main/Chapter-08.ipynb)
9. [Predicting Continuous Target Variables with Regression Analysis.](https://nbviewer.jupyter.org/urls/raw.githubusercontent.com/YaoXiao-CS/Python-MachineLearning/main/Chapter-09.ipynb)
10. [Working with Unlabeled Data – Clustering Analysis.](https://nbviewer.jupyter.org/urls/raw.githubusercontent.com/YaoXiao-CS/Python-MachineLearning/main/Chapter-10.ipynb)
11. [Implementing a Multi-layer Artificial Neural Network from Scratch.](https://nbviewer.jupyter.org/urls/raw.githubusercontent.com/YaoXiao-CS/Python-MachineLearning/main/Chapter-11.ipynb)
12. [Parallelizing Neural Network Training with PyTorch.](https://nbviewer.jupyter.org/urls/raw.githubusercontent.com/YaoXiao-CS/Python-MachineLearning/main/Chapter-12.ipynb)
13. [Going Deeper -- The Mechanics of PyTorch.](https://nbviewer.jupyter.org/urls/raw.githubusercontent.com/YaoXiao-CS/Python-MachineLearning/main/Chapter-13.ipynb)
14. [Classifying Images with Deep Convolutional Neural Networks.](https://nbviewer.jupyter.org/urls/raw.githubusercontent.com/YaoXiao-CS/Python-MachineLearning/main/Chapter-14.ipynb) 
15. Modeling Sequential Data Using Recurrent Neural Networks. [TODO]
16. Transformers -- Improving Natural Language Processing with Attention Mechanisms. [TODO]
17. [Generative Adversarial Networks for Synthesizing New Data.](https://nbviewer.jupyter.org/urls/raw.githubusercontent.com/YaoXiao-CS/Python-MachineLearning/main/Chapter-17.ipynb)
18. Graph Neural Networks for Capturing Dependencies in Graph Structured Data. [TODO]
19. Reinforcement Learning for Decision Making in Complex Environments. [TODO]
