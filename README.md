  
The model can work on both GPU and CPU.
For it to work on CPU, clone the yolo5 repository from github and:

pip install tqdm
pip install numpy
pip install pillow
pip install scipy
pip install pyyaml
pip install matplotlib
pip install opencv-python==4.1.2.30
***pip install torch==1.7.0+cpu torchvision==0.6.1+cpu -f https://download.pytorch.org/whl/torch_stable.html*** This line is the most important

**checklist
# pip install -r requirements.txt

# base ----------------------------------------
matplotlib>=3.2.2
numpy>=1.18.5
opencv-python>=4.1.2
Pillow
PyYAML>=5.3.1
scipy>=1.4.1
torch>=1.7.0
torchvision>=0.8.1
tqdm>=4.41.0

# logging -------------------------------------
tensorboard>=2.4.1
# wandb

# plotting ------------------------------------
seaborn>=0.11.0
pandas

# export --------------------------------------
# coremltools>=4.1
# onnx>=1.8.1
# scikit-learn==0.19.2  # for coreml quantization
