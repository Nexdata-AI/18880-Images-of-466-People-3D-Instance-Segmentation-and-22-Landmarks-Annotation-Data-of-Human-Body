# 18880-Images-of-466-People-3D-Instance-Segmentation-and-22-Landmarks-Annotation-Data-of-Human-Body
https://www.datatang.ai/datasets/1040

## Description
18,880 Images of 466 People - 3D Instance Segmentation and 22 Landmarks Annotation Data of Human Body. The dataset diversity includes multiple scenes, light conditions, ages, shooting angles, and poses. In terms of annotation, we adpoted instance segmentation annotations on human body. 22 landmarks were also annotated for each human body. The dataset can be used for tasks such as human body instance segmentation and human behavior recognition.

## Data size
466 people, the number of  images is 18,880

## Race distribution
Asian

## Gender distribution
233 males, 233 females

## Age distribution
299 children and teenagers, 167 adults

## Collecting environment
including indoor scenes and outdoor scenes

## Data diversity
multiple scenes, light conditions, ages, shooting angles, and poses

## Device
RealSense Depth Camera D435i

## Data format
the image data format is .jpg and .png, the annotation file format are .json，the file format of camera parameters is .txt

## Collecting content
3D images of various human body poses ((the rgb channel and depth channel have been registered))

## Annotation content
instance segmentation annotation of human body , 22 landmarks annotation of human body

## Accuracy
Accuracy requirement: the mask edge location errors in x and y directions are less than 3 pixels, which is considered as a qualified annotation;  Accuracy requirement of segmentation annotation: the annotation part (each part of mask) is regarded as the unit, the accuracy rate shall be more than 95%; Accuracy requirement of landmark annotation: the annotation part (each landmark) is regarded as the unit, the accuracy rate shall be more than 95%; Annotating accuracy = number of correct annotations / total number of annotations
