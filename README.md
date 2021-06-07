# Bangkit-Final-Project

This is B21-CAP0124 Bangkit final project repository for machine learning section which create TFLite model as the output. We used MobileNetV2 for object detection provided by [TensorFlow API](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md) and dataset from [Kaggle](https://www.kaggle.com/akkithetechie/furniture-detector).

Our members team:

1. Yang Febriana Nur Firdauzy
2. Ardianto Hermawan Nawir
3. Muhammad Hernanda
4. Mohamad Rafli Agung Subekti
5. Julius Ivander Massie
6. Dwi Fristanti Sagala

# Getting Started

## TensorFlow Object Detection API Installation

### 1. Downloading the TensorFlow Model Garden

TensorFlow Model Garden provided some setup for us to for object detection preparation and make sure to put it inside the `TensorFlow` folder

```
TensorFlow/
└─ models/
```

### 2. Protobuf Installation/Complilation, Object Detection API Installation, Train and Obtain TFLite Model

Once we downloading the TensorFlow Model Garden, save the project file into Google Drive and run `train_model_gpu.ipynb` in google colab. Make sure to turn on the GPU that provided by google colab.

After running the jupyter notebook file, TFLite model will be found in `TensorFlow/workspace/training_demo/exported-models/my_model_v2/TFLite_Graph/model.tflite` from your google drive.
