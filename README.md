# Yolo-Licenseplate-detection-and-recognition
Yolo系列的车牌检测与PaddleOCR的车牌识别系统
可检测和识别：蓝色车牌、绿色车牌、黄色车牌
### 环境配置(CPU版本,可自选，GPU可自行更改)：
```bash
conda create -n YoloPaddle python==3.9
conda activate YoloPaddle 
pip install torch==2.0.1 torchvision==0.15.2 torchaudio==2.0.2 --index-url https://download.pytorch.org/whl/cpu
pip install -r requirements.txt
```

### 运行：
```bash
python detect.py
```
### 车牌检测结果示例
![车牌检测结果](https://github.com/xtl-131/Yolo-Licenseplate-detection-and-recognition/demo/demo.png"车牌检测结果")
# 车牌检测数据集
### 来源于部分CCPD和CRPD，可直接进行Yolo系列模型进行训练
# 车牌识别数据集
### 来源于部分CCPD、CRPD和全部CBLPRD，可直接进行PaddleOCR模型进行训练
### 需要数据集或者车牌检测识别界面系统请联系v:xtl-131
