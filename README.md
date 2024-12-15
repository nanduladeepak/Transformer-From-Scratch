# Transformer-From-Scratch
Implementing Pre trained transformer from scratch using PyTorch

## Setup PyTorch environment using conda for m1 mac
### Conda setup environment pt_env (machine learning PyTorch) with pytorch
```
$ CONDA_SUBDIR=osx-arm64 conda create -n pt_env python=3.10 -c conda-forge
conda create -n pt_env python=3.10 -y
```

### To activate this environment, use
```
$ conda activate pt_env
```

### run below command once first time activation of the environment
conda env config vars set CONDA_SUBDIR=osx-arm64

## Install PyTorch
```
$ pip install -U --pre torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/nightly/cpu
$ conda install pytorch::pytorch torchvision torchaudio -c pytorch
$ pip install torch torchvision torchaudio
```

## Install other ml  libraries
```
$ conda install pandas jupyter jupyterlab scikit-learn matplotlib opencv seaborn ipykernel
```

## Install HuggingFace transformers
```
$ curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
$ pip install transformers datasets
```

pip install transformers==4.30.2

conda create -n pt_env python=3.10 -y
conda activate pt_env
pip install torch torchvision torchaudio transformers datasets
conda install pandas jupyter jupyterlab scikit-learn matplotlib opencv seaborn ipykernel
<!-- pip install transformers datasets -->
conda install -p /opt/anaconda3/envs/pt_env ipykernel --update-deps --force-reinstall


conda create -n pt_env python=3.10 -y
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/cpu
conda install pandas jupyter jupyterlab scikit-learn matplotlib opencv seaborn
pip install transformers


url --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
conda create -n pt_env python=3.10 -y
conda activate pt_env
conda install pytorch::pytorch torchvision torchaudio -c pytorch
conda install pandas jupyter jupyterlab scikit-learn matplotlib opencv seaborn tokenizers datasets
conda install -c huggingface transformers