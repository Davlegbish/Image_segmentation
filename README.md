# Image Segmentation using Mask R-CNN (maskrcnn_resnet50_fpn)

Image segmentation is a critical task in computer vision that involves partitioning an image into multiple segments or objects, making it easier to analyze or process. This note provides an extensive explanation of implementing image segmentation using the maskrcnn_resnet50_fpn model.

# Overview of Mask R-CNN
Mask R-CNN is an extension of Faster R-CNN that includes a branch for predicting segmentation masks on each Region of Interest (RoI). This model is widely used for object detection and instance segmentation tasks.

Key components of Mask R-CNN:
1.Backbone (Feature Extractor): ResNet-50 with Feature Pyramid Network (FPN) is used to extract features from images.

2.Region Proposal Network (RPN): Proposes candidate object regions.

3.ROIAlign: Precisely extracts features for each candidate region.

4.Classification, Bounding Box Regression, and Mask Prediction: Performs object detection and instance segmentation.

# Prerequisites
Python Libraries:

1.PyTorch: For model implementation and training.  

2.Torchvision: Provides pre-trained maskrcnn_resnet50_fpn. 

3.OpenCV: For image processing and visualization.

4.Matplotlib: For plotting results.

5.NumPy: For numerical operations.

6.Dataset: Prepare a dataset with images, bounding boxes, and corresponding masks. You can use formats like COCO, Pascal VOC, or custom datasets.

7.PIL: it provides a convenient way to handle image processing tasks, such as opening, displaying, and saving images.


# Before Segmentation

![Screenshot (67)](https://github.com/user-attachments/assets/c2ad161c-9457-4374-9eba-e3a1f7c55af3)


# After Segmentation

![Screenshot (68)](https://github.com/user-attachments/assets/4d4dba80-d1f0-45e3-8a60-550ae4d7617c)


# Results

![Screenshot (69)](https://github.com/user-attachments/assets/5e6e92af-e67c-4daf-ba84-fd3d837489aa)




