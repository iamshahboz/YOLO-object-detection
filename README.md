### YOLO - real time object detection tool

#### If predefined yolo model can not predict your object you have to train a custom model on the top of yolo model

## Requirements 
1. As you might already know for machine learning task including this one it is better to use
Jupyter Notebook or Google Colab. Make sure you have one of them in your pc

## Labeling
Before you start training a custom model you have to annotate(label) the hundereds of images.
Labeling means drawing bounding box around the object for which you want to train a custom model.
The recommended environment for labeling images in Roboflow 
```bash
https://app.roboflow.com
```
1. Create an account in roboflow
2. In a Projects section, click New Project Button 
3. Name your project, for the annotation group name your object(objects) for which you are going to train 
4. For the project type select Object Detection
5. In the upload data section, upload images of the object
6. Save it
7. Annotate them
8. Add to the dataset
9. In a versions section hit next next and generate a version
10. Click download dataset in a upper right corner, select Yolov8 and continue
11. Copy the code under the Jypyter section


## Model training
1. You can run the commands mentioned in target_detection.ipunb one by one 
