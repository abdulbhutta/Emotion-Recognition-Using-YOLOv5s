
Emociones - v1 640x640
==============================

This dataset was exported via roboflow.com on June 27, 2023 at 5:17 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 6295 images.
Emotions are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* Randomly crop between 0 and 10 percent of the image
* Random rotation of between -8 and +8 degrees
* Random shear of between -8° to +8° horizontally and -6° to +6° vertically
* Random Gaussian blur of between 0 and 2.75 pixels
* Salt and pepper noise was applied to 2 percent of pixels


