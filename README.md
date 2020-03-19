# TrafficSignRecognitionSystem
In this project, I used Python and TensorFlow to classify traffic signs.

Dataset used: German Traffic Sign Dataset. This dataset has more than 50,000 images of 43 classes.

This project deals with comparing the best ways of image processing using different contrast enhancement and then using these images to train CNN models on different architectures. 

The contrast enhancement techniques used are-
1. Gamma Transformation (GT)
2. Linear Histogram Equalization (LHE)
3. Contrast Limited Adaptive Histogram Equalization (CLAHE)

The CNN architectures used are-
1. LeNet architecture
2. VggNet architecture
3. ResNet architecture

I have trained the model and found out that the best technique of contrast enhancement is CLAHE and the architecture on which we can get best accuracy is ResNet architecture.
