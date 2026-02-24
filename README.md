##Animal Detection using Computer Vision
Overview
This project implements an animal detection model using computer vision techniques. The model is trained to recognize various animals and detect them in camera.

Requirements
Before running the code, ensure you have installed the required dependencies. The necessary libraries are listed in requirements.txt.

Running the Project
1. Open the Jupyter Notebook (animaldetection.ipynb).

2. Run the cells sequentially to execute the model training and detection.
	for installing the required dependencies i have added:  pip install -r requirements.txt

run that cell first. it will take some time to install the dependencies.. after installation run the 2nd cell which has main code of the project... it will take some time to open the WEB cam.. then it will detect the animals with bounding boxes around detected animals, along with confidence scores.
It will automatically download the yolovn8.pt dataset.		
	
Dependencies:
The main dependencies for this project include:

OpenCV (opencv-python==4.11.0.86) – for image processing

Ultralytics (ultralytics==8.3.70) – for YOLO-based detection models
