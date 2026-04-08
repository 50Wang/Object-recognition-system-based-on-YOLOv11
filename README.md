# Object-recognition-system-based-on-YOLOv11
使用YOLOv11预训练模型，实现对图像中常见物体的定位与识别，数据集为COCO子集。/Using the pre-trained YOLOv11 model, the recognition and positioning of common objects in images are achieved. The dataset is a subset of COCO.

预训练模型权重(yolo11n.pt)是ultralytics官方用COCO数据集训练好的，可以识别person, car, dog, cat等80个常见类别。

将要进行识别的图像放入yolov11-master\data\images，运行detect.py，结果在yolov11-master\runs\detect新出现的exp文件夹中，如图：

![image_000002](https://github.com/user-attachments/assets/bd3d4600-47a4-4fa4-94a8-3c7faf00d88f)

如果想用自己的数据集来训练，数据集需要image+label(同名仅文件类型不同)，运行train_v11.py，训练结果在yolov11-master\runs\train\exp。
