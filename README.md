# Emotion Recognition Using YOLOv5s
### Abdul Bhutta
### EE8108 - Multimedia Processing and Communication

This is a final project for EE8108: Multimedia Processing and Communication
Dataset: https://universe.roboflow.com/uemc-y7rsy/emociones

The project implements a generalized model to detect emotions through an image.

![alt text](https://github.com/abdulbhutta/Emotion-Recognition-Using-YOLOv5s/blob/main/Images/Image.jpg)

## Getting Started

Please look below on how to run the code or model! DO NOT RUN THE TRAIN SECTION OF THE NOTEBOOK! IT WILL OVERRIDE THE TRAINED PARAMETERS AND WEIGHTS!

### Prerequisites

Download or Clone this repo.
* Please update the path names to the correct location!
  ```sh
  #Path to the test images 
  image_path = '/Users/abdulbhutta/Desktop/Multimedia_FinalProject/Emotion_Detection/train/images/test1.png'
  model_path = '/Users/abdulbhutta/Desktop/Multimedia_FinalProject/Final_Project/yolov5'
  To your own paths!

  #The Model Best Parameters can be found here: /runs/train/yolov5s_results/weights/best.pt
  ```

### Train/Run the Model

Below is an example of how you Train or Test your own model. You must change the path and import the libraries!

To Train: Go to the Train Section in the Notebook
   ```sh
   Run the Import Libraries and Install Dependencies (4 Cells)
   Either Run the Roboflow setup or upload your own dataset and Change path names accordingly
   ```
To Test: Go to the Test your Own Image with the model section
   ```sh
   Update the path to the location of the image!
   Run the 4 Cells
   ``` 
