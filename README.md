# Lightweight CNN for Drone-Based Crop Disease Detection vs MobileNetV3Small & ResNet50

This project investigates lightweight and efficient deep learning models for early crop disease classification using drone imagery. Three Models were evaluated on the PlantVillage dataset: a custom lightweight CNN, MobileNetV3-Small, and ResNet50.

The proposed custom CNN contains only 0.64M parameters and achieved 90.60% validation accuracy with an inference time of 0.07 seconds per image, making it suitable for real-time deployment on drone platforms. Despite its small size, the model outperformed MobileNetV3-Small and ResNet50.

## Features
- Custom lightweight CNN with only six layers
- Achieved 90.60% validation accuracy
- 37 times smaller than ResNet50
- Real-time inference (0.07 seconds per image)
- Experiments with MobileNetV3-Small and ResNet50 for comparison
- Analysis of data augmentation effects

## Dataset
- PlantVillage dataset

## Future Work
- Additional preprocessing techniques
- Evaluation on PlantDoc and real drone datasets

## Technologies
- TensorFlow / Keras
- Python
