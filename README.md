# number-plate-recognition-system
Recognizes the number plate ID from a given frame of vehicles.

The model has been trained on a Keras version of the YOLOv3 model.

Requirements:
1. Keras = 2.1.5
1. Tensorflow = 1.6.0
1. OpenCV
1. PyTesseract for OCR

The dataset and model weights are available here:
[number-plate-recognition](https://drive.google.com/open?id=1MzkFwI7dv7yo0JcjAm9N5IodEB1J9gxo)
The dataset is of the Google OpenImage Dataset "Vehicle registration plate" class.

The number plates are recognised as follows:
![car1-detect](/test/detect1.jpg)

![car1-detect](/test/detect2.jpg)

References:
* [qqwwee](https://github.com/qqwweee/keras-yolo3) - Keras version of YOLOv3
