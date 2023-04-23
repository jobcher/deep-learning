# deep-learning
deep-learning
## 安装环境
```sh
conda create -n deep-learning python=3.10
conda activate deep-learning
conda install jupyter notebook
```
### 安装CPU版本的PyTorch
```sh
conda install pytorch torchvision torchaudio cpuonly -c pytorch
pip install torch torchvision matplotlib
```

### 安装GPU版本的PyTorch
```sh
conda install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia
pip install torch torchvision matplotlib
```