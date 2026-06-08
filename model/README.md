# Models

This directory contains trained deep learning models used in the Tyre Defect Detection project.

## Current Model

* `tyre_classifiercnn.keras` — MobileNetV2-based transfer learning model trained for tyre/non-tyre image classification.

## Model Details

* Architecture: MobileNetV2
* Framework: TensorFlow / Keras
* Input Size: 224 × 224 × 3
* Task: Binary Image Classification
* Output:

  * 0 → Non-Tyre
  * 1 → Tyre

The model is trained on preprocessed tyre image data and can be used for inference on unseen images.

Future versions will include YOLO-based models for tyre defect detection and localization.
