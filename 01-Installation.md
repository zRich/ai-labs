# 本教程用于安装一个 transformer 环境

## Python

3.10 版本

### 虚拟环境

venv

### 创建环境

```bash
python3 -m venv venv_name
```

创建虚拟机后，会在目录生成多个python运行环境相关的文件。为了使环境更加简洁、便于维护，在其中创建一个工作目录 `workspace`。`workspace`目录下 `datasets`子目录和 `models` 子目录存放需要项目用到的数据集和模型。

## Jupyter Lab

```bash
pip install jupyterlab
```

### Jupyter Console

```bash
pip install jupyter-console
```

### 启动 Jupyter

```bash
jupyter lab --ip=0.0.0.0 workspace
```

## HuggingFace

由于很多 AI 模型和数据集都比较大，因此系统上需要安装 git 大文件支持。

```bash
sudo apt-get install git-lfs
```

### 数据集和模型下载

可以看到有很多工具帮助下载，但是效果都不甚理想。个人经验最好的办法是科学上网，然后通过浏览器直接下载数据集和模型的文件。
