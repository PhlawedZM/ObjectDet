# Object Detection in Android

Implementation of Quantized TFlite models in android.
[Demonstration](https://youtu.be/p8af3-unmQA)

## Installation Instructions

Follow these steps to get the project up and running on your local machine:

### Prerequisites
Make sure you have the following installed:

- [Python](https://www.python.org/)
- [Android Studio](https://developer.android.com/studio)
- [Tensorflow 2 Model](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md)

### Cloning the Repository
First, clone this repository to your local machine using Git:

```bash
git clone https://github.com/PhlawedZM/ObjectDet.git
cd ObjectDet
```


### Turning the model into tflite
Second, we have to turn these models in tflite format. Run this line in main.py


```bash
export_saved_model('your_saved_model')
```


### Sync Gradle
Third, set up gradle imports by syncing.
You should be running.
