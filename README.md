# Document-scanner-app-with-Optical-Character-Recognition.
This repository contains a  document scanner app that could perform Optical Character Recognition.

Here the approach is taken to build an app that can scan a document, crop the document and then perform Optical Character Recognition. 

The app is developed using Android Studio and Java.

Libraries used for above processes are:
1. Google's ML Kit Text Recognition API
2. ArthurHub/Android-Image-Cropper

Given below is a test scenario of the app developed. Here we scan the document, crop the relevant part for OCR and then display the text in another activity. This app can be further improved to use this captured text in some other process.

### Test 1

<p align='left'>
    <img src="./figures/test 1/doc.png" alt="drawing" width="200"/>
    <img src="./figures/test 1/OCR.png" alt="drawing" width="200"/>
</p>

https://user-images.githubusercontent.com/56619402/223026634-bd4a0783-a295-4d62-9eee-4ea736faa05b.mp4

### Test 2

<p align='left'>
    <img src="./figures/test 2/doc.png" alt="drawing" width="200"/>
    <img src="./figures/test 2/OCR.png" alt="drawing" width="200"/>
</p>

https://user-images.githubusercontent.com/56619402/223027534-541a916a-98fa-4dcc-b410-c86a728652ea.mp4

### Confusion matrix

Finally the accuracy of the app is tested using practical scenarios and confusion matrix is created to evaluate the output. For the 150 words recognized, the confusion matrix is as follows.

![image](https://user-images.githubusercontent.com/56619402/223024547-9a6d01ed-c43c-4aef-b009-9c33349e4b40.png)

1. Accuracy = (TP+TN)/(TP+TN+FP+FN) = 0.9266
2. Precision = TP/(TP+FP) = 0.9858
3. Recall = TP/(TP+FN) = 0.9391

