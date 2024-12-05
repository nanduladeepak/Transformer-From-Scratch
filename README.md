# Transformer-From-Scratch
Implementing Pre trained transformer from scratch using PyTorch

## Setup PyTorch environment using conda for m1 mac
### Conda setup environment mlpt (machine learning PyTorch) with pytorch
```
$ CONDA_SUBDIR=osx-arm64 conda create -n mlpt python=3.9 -c conda-forge
```

### To activate this environment, use
```
$ conda activate mlpt
```

### run below command once first time activation of the environment
conda env config vars set CONDA_SUBDIR=osx-arm64

## Install PyTorch
```
$ pip install -U --pre torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/nightly/cpu
```

## Install other ml  libraries
```
$ conda install pandas jupyter jupyterlab scikit-learn matplotlib opencv seaborn
```

## Install HuggingFace transformers
```
$ curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
$ pip install transformers datasets
```