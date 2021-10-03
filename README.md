# License plate Detection and Recognition

This repository includes detecting License plates of vehicles and recognising them using OCR from real time videos.

Detecting License plate and recognising them have a wide applications in the real world.
I used the basic methods for detecting License plate and recognising them using OCR(Optical Character Recognition). The input video will be converted to images, and the preprocessing methods are performed.

1. Pre-processing

Gaussian Blur

Sobel Edge Detection

Binarization

Erosion and Dilation

2. Detect License plates by Contour Detection

Extract license plate contour by defining minimum area rectangle

3.  Extract Character Candidates by Connected Component Analysis(CCA) and Contour Detection

4. Predict characters by OCR pre-trained model


Results

![Capture1](https://user-images.githubusercontent.com/71822090/133805169-7711e6b3-929b-4f10-b69d-e5108399bf6a.JPG)

![Capture2](https://user-images.githubusercontent.com/71822090/133805224-2ba10115-7a30-4348-831d-2e75c8242841.JPG)

Reference

https://www.geeksforgeeks.org/detect-and-recognize-car-license-plate-from-a-video-in-real-time/









