# GFormer 

这是对GFormer模型的复现项目，包括运行代码和实验结果。

## 目录

- [项目简介](#项目简介)
- [安装和使用](#安装和使用)
- [数据准备](#数据准备)
- [训练代码](#训练代码)



## 项目简介

本项目旨在复现GFormer模型的实验结果，提供了详细的代码和使用说明。所有代码均已上传至Google Drive，可以通过Google Colab运行。

## 安装和使用

### 依赖项

- Python 3.6或以上版本
- 必要的Python库
- cuda

### 运行项目

在Google Colab中运行代码时，请将项目文件上传到Google Drive，并挂载到Colab环境中。

## 数据准备

以movielens-ml50M数据集为例，准备数据集并放置在指定目录中。

## 训练代码

使用以下命令运行训练代码：

### Movielens-ml20M


```bash
python Main.py --data movielens --reg 1e-4 --ssl_reg 1 --gcn 3 --ctra 1e-3 --b2 1 --pnn 1
```


