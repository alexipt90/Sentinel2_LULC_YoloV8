YOLOv8 Object Detection on Sentinel-2 LULC Dataset

Project Overview:
This project implements an object detection model using YOLOv8 to detect various land cover classes from the Sentinel-2 Land Use Land Cover (LULC) dataset. The model is capable of identifying the following classes:

    River
    Built Area
    Trees
    Crops
    Bare Ground
    Snow
    Rangeland

Dataset

The model has been trained on the Sentinel-2 LULC dataset, which consists of satellite images annotated with various land cover classes. The dataset is split into training and validation sets as defined in the train.yaml file included in this repository.

Pre-trained Model

A pre-trained YOLOv8 model is provided in the weights folder. This model has been fine-tuned on the Sentinel-2 LULC dataset and can be used directly for inference.


Sample Images

The sample_images folder contains some sample images from the dataset, along with their respective annotations. You can use these images to test the model and visualize its predictions.