# YOLO-Waste-Detection

## Installation

```
conda create --name yolo python=3.10 -y
conda activate yolo

pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121

pip install asone

pip install flask
pip install flask_wtf
pip install flask_bootstrap
pip install flask_socketio
```

https://pytorch.org/get-started/locally/

conda info --envs

conda env remove --name yolo -y

## Test

```
python flaskApp.py
```

![example1](/assets/1.jpg)

## Datasets

https://universe.roboflow.com/material-identification/garbage-classification-3
