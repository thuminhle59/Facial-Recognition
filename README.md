# FACIAL RECOGNITION

## Project Description
This project was done in a team of 3 members, each member applied a different approach from Face-recognition package, CascadeClassifer of OpenCv, to Yolo3 with DNN model. In this repository are the solution for Facial Identification using 2 approaches Yolo3 and Face-recognition package

---------------------------------
## 1st Approach: Image Detection with YOLOv3 & Classfication by DNN

### Models
| Model name      | Purpose | Pre-trained dataset | Transfer Learning |
|-----------------|------------------|------------------|------------------|
| Yolov3| Facial Detection | COCO | No |
| Xception| Facial Identification | ImageNet | Yes |

### Description
This model uses Xception architecture for Transfer Learning, and is trained on 300 images of 3 classes using the last 27 layers in the network. The classifier is a Dense layer with a "softmax" activation function

### Training Data
300 images of 3 classes have been used for the purpose of training the classifier of this project. The image is taken with either a laptop's webcam or cell-phone and cropped so that only the faces are in the images. Image Augmentation was applied to expand the dataset and reduce the potention of overfitting.

### Performance
The accuracy for the final model is 100% 

-------------------------------------------------
## 2nd Approach: Using face_recognition package

### Package summary:
- Recognize and manipulate faces from Python with the world's simplest face recognition library
- Built using [dlib](http://dlib.net/)'s state-of-the-art face recognition built with deep learning. The model has an accuracy of 99.38% on the [Labeled Faces in the Wild](http://vis-www.cs.umass.edu/lfw/) benchmark.
- Go to this [link](https://github.com/ageitgey/face_recognition) for more information
### Some main features:
- Find faces in picture:

<p align="center">
  <img src="https://cloud.githubusercontent.com/assets/896692/23625227/42c65360-025d-11e7-94ea-b12f28cb34b4.png" alt="Sublime's custom image"/>
</p>
  
- Find and manipulate facial features in pictture:
	Get locations and outlines of each person's eyes, nose, mouth and chin.
	
<p align="center">
  <img src="https://cloud.githubusercontent.com/assets/896692/23625282/7f2d79dc-025d-11e7-8728-d8924596f8fa.png" alt="Sublime's custom image"/>
</p>

- Connect with OpenCV for real-time face recognition:

<p align="center">
  <img src="https://cloud.githubusercontent.com/assets/896692/24430398/36f0e3f0-13cb-11e7-8258-4d0c9ce1e419.gif" alt="Sublime's custom image"/>
</p>

### Workflow:

<p align="center">
  <img src="https://user-images.githubusercontent.com/87942072/135027253-2ddbff24-3e06-4232-802c-acd92cca945d.png" alt="Sublime's custom image"/>
</p>


