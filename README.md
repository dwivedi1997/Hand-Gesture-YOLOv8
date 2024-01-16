# Hand Gesture Detection - YOLOV8
Please consider following this project's author, Aniket Dwivedi, and consider starring the project to show your ❤️ and support.

# Dataets
Roboflow API was used to download the dataset: <br>

!pip install roboflow<br>
from roboflow import Roboflow<br>
rf = Roboflow(api_key="api_key")  # API key can be downloaded from roboflow user account<br>
project = rf.workspace("lebanese-university-grkoz").project("hand-gesture-recognition-y5827")<br>
dataset = project.version(6).download("yolov8")

# YOLOV8
YOLOv8 is the latest version of YOLO by Ultralytics. As a cutting-edge, state-of-the-art (SOTA) model, YOLOv8 builds on the success of previous versions, introducing new features and improvements for enhanced performance, flexibility, and efficiency. YOLOv8 supports a full range of vision AI tasks, including detection, segmentation, pose estimation, tracking, and classification. This versatility allows users to leverage YOLOv8's capabilities across diverse applications and domains.


# Training
All the codes associated with the YOLOv8 training can be found in the google colab notebook <a href='https://colab.research.google.com/drive/1SvcNtVWY9283iOsB2sHmpgiOgR0SEZtJ?authuser=1#scrollTo=RZpNfszhQIEe'> Hand gesture </a><br>

The following is the anotate image of the training dataset:<br>
<img src='https://github.com/dwivedi1997/Hand-Gesture-YOLOv8/blob/main/runs/detect/train/train_batch1.jpg'></img>

