# Object Detection Project

This project focuses on training and deploying an object detection model using the YOLO (You Only Look Once) algorithm to detect various items of safety gear in videos and images.

## Workflow

1. **Dataset Selection**: Choose the dataset from YouTube and sample videos containing instances of safety gear items such as helmets, gloves, goggles, and boots.

2. **Data Annotation**: Annotate the images using Roboflow to label the different classes of objects in the dataset, including "helm", "nohelm", "glove", "noglove", "goggles", "nogoggles", and "boots".

3. **Dataset Preparation**: Organize and prepare the annotated dataset for training with the YOLO model. This includes converting annotations into the YOLO format.

4. **Model Training**: Train the YOLO model using the prepared dataset to learn to detect the specified classes of objects accurately. Utilize Roboflow's pre-trained model capabilities to accelerate the training process.

5. **Model Evaluation**: Evaluate the trained model's performance on a separate test dataset to assess its accuracy and effectiveness in detecting safety gear items.

6. **Model Deployment**: Once the model is trained and evaluated, deploy it for use in real-world scenarios. This could involve integrating the model into an application or deploying it on edge devices for real-time object detection.

## Getting Started

### Prerequisites

Python, OpenCV, Roboflow, supervision.

### Installation

Provide step-by-step instructions on how to set up the project environment, install dependencies, and run the code.
