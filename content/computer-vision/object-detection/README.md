[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BoumedineBillal/object-detection-yolo/blob/main/yolo_workshop.ipynb)

# Object Detection YOLO

![Custom IoU Metric](https://drive.google.com/uc?export=view&id=1_wrJsUf77Yk116nnpp-zhkeuHymnAFwY)

Welcome to the Object Detection YOLO Workshop! This repository contains a simplified implementation of object detection using the YOLO (You Only Look Once) algorithm. The goal is to provide an educational resource for understanding the fundamentals of YOLO-based object detection.

## Features

- Simplified YOLO-based object detection implementation
- Custom IoU (Intersection over Union) metric for model evaluation
- Step-by-step workshop agenda for hands-on learning

## Agenda

1. **Setting Up Kaggle and Downloading Car Plate Detection Dataset**
   - Install Kaggle API for dataset download
   - Upload Kaggle API key
   - Download the car plate detection dataset from Kaggle

2. **Data Preprocessing and YOLO Labeling**
   - Load and preprocess the dataset
   - Implement YOLO labeling for object detection
   - Split the data into training and testing sets

3. **Custom IoU Metric Function**
   - Implementation of a custom IoU metric function
   - Understanding IoU threshold and its significance

4. **YOLO-based Object Detection Model Architecture**
   - Designing the architecture of a YOLO-based object detection model
   - Introduction to probability and bounding box prediction

5. **Train the Model**
   - Compilation of the model with a custom IoU metric
   - Training the YOLO-based object detection model

6. **Test the Model**
   - Evaluation of the trained model on test data
   - Visualization of model predictions
   - Discussion of results and potential improvements

7. **Workshop challenge**
   - The challenge is to implement the `calculate_grid_for_point` function, which takes a point's x and y coordinates along with the grid size and returns the corresponding grid indices.
   
## Prerequisites

- Basic knowledge of Python and deep learning concepts.
- Google Colab account for an interactive learning experience.

## Getting Started

1. Clone this repository.
2. Follow the workshop agenda step by step.

## Resources

- [Link to Kaggle dataset](https://www.kaggle.com/andrewmvd/car-plate-detection)
- Additional resources and references will be provided during the workshop.

## Colab Notebook

- [Colab Notebook](https://github.com/BoumedineBillal/object-detection-yolo/blob/main/yolo_workshop.ipynb)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
