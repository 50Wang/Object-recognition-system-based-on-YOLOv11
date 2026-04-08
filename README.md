# Object-recognition-system-based-on-YOLOv11
使用YOLOv11预训练模型，实现对图像中常见物体的定位与识别，数据集为COCO子集。/Using the pre-trained YOLOv11 model, the recognition and positioning of common objects in images are achieved. The dataset is a subset of COCO.

预训练模型权重(yolo11n.pt)是ultralytics官方用COCO数据集训练好的，可以识别person, car, dog, cat等80个类别。

将要进行识别的图像放入yolov11-master\data\images，运行detect.py，结果如图：

![image_000002](https://github.com/user-attachments/assets/bd3d4600-47a4-4fa4-94a8-3c7faf00d88f)


