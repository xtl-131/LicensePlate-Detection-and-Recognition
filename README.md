# Yolo-Licenseplate-detection-and-recognition
Yolo系列的车牌检测与识别系统
### 环境配置(CPU版本,可自选，GPU可自行更改)：
```bash
conda create -n YoloPaddle python==3.9
conda activate YoloPaddle 
pip install torch==2.0.1 torchvision==0.15.2 torchaudio==2.0.2 --index-url https://download.pytorch.org/whl/cpu
pip install -r requirements.txt
