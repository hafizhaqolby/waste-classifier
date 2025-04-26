# Waste Classification Image Classification Project

This project builds an image classification model to classify waste into different categories using TensorFlow.  
The model is trained, evaluated, and saved in multiple formats (SavedModel, TFLite, and TensorFlow.js).

## Folder Structure
```
│-- saved_model/
│   │-- saved_model.pb
│   │-- fingerprint.pb
│   │-- variables
│-- tfjs_model/
│   │-- group1-shard1of5.bin
│   │-- group1-shard2of5.bin
│   │-- group1-shard3of5.bin
│   │-- group1-shard4of5.bin
│   │-- group1-shard5of5.bin
│   │-- model.json
│-- tflite/
│   │-- model_waste.tflite
│   │-- label.txt
│-- [Final]_Image_Classification.ipynb
│-- README.md
│-- requirements.txt
```
## Installation

Install the dependencies by running:

```bash
pip install -r requirements.txt
