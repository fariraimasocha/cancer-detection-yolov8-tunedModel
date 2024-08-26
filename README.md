# YOLOv8 Cancer Cell Detection

This project utilizes the YOLOv8 model with the Roboflow cancer dataset to create a custom model for detecting cancer cells. Follow the instructions below to run the Jupyter Notebook and use the trained model.

## Running the Jupyter Notebook

### Prerequisites

Make sure you have the following libraries installed:

```bash
pip install ultralytics roboflow

from ultralytics import YOLO


# Load the trained model
model = YOLO('path/to/runs/train/2/weights/best.pt')

# Perform inference on an image
results = model.predict(source='path/to/your/image.jpg')

#Running the Notebook
Execute each cell in the notebook sequentially. Ensure that your dataset is correctly formatted and accessible as specified in the data.yaml file.

## Additional Notes
If you are working on a similar project, feel free to use the provided code and insights from the notebook. The YOLOv8 framework, combined with Roboflow, simplifies the creation of custom CNN models for various applications, including cancer detection.
For more detailed insights, check the Jupyter Notebook for examples of how to train and evaluate your model effectively. This will help you understand the workflow and capabilities of YOLOv8 and Roboflow in building object detection models.
