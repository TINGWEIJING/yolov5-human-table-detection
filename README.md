# Yolo
## Quick Run
### Create Python `venv`
```bash
python3 -m venv venv
```

### Activate `venv`
```bash
source ./venv/bin/activate
```

### Install Dependencies
```bash
pip install -r requirements.txt

# install PyTorch
pip3 install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cpu
```

### Quick Run
```bash
python inf.py --weights yolov5n.pt --source 0
```