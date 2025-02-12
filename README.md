Plant Disease Detection: RGB and Thermal Imaging

Datasets:-
RGB Dataset: https://github.com/spMohanty/PlantVillage-Dataset/tree/master/raw/color
Thermal Dataset: https://www.kaggle.com/datasets/sujaradha/thermal-images-diseased-healthy-leaves-paddy

Models used
- UNet
- SegNet
- ResNet
- GoogleNet
- VGG
- AlexNet
- Inception V3
- EfficientNetV2
- ViT
- R-CNN
- YOLOv11

RGB Dataset Accuracies

Model	           |      Accuracy (%)
-------------------|-----------------
ViT	               |       98.08
ResNet	           |       96.80
Inception V3	   |       93.50
EfficientNetv2	   |       93.20
AlexNet	           |       93.08
VGG	               |       91.20
GoogleNet	       |       90.27
SegNet	           |       90.10
UNet	           |       92.71
YOLOv11	           |       62.67


Thermal Dataset Accuracies

Model	           |    Test Accuracy (%)
-------------------|---------------------
EfficientNetv2     |       	94.53
ResNet 50/101	   |        92.19/89.84
UNet	           |        97.2
Inception V3	   |        75.87
SegNet	           |        95.01
GoogleNet	       |        93.3
AlexNet            |      	88.28
VGG                |     	87.50
RCNN	           |        98.65
ViT	               |        92.97
