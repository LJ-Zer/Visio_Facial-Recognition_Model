# INSIDE THE FOLDER EXECUTE THIS IN TERMINAL!!

## Preparation

### Install Anaconda
- Create Virtual Environment
  - conda create --name inference python=3.9
- Activate the Environment
  - conda activate inference
- Install Dependencies
  - pip install tensorflow opencv-python protobuf==3.20.*

### Inferencing 

- Activate the Environment
  - conda activate inference
- Run for Inferencing
  - python TFLite_detection_webcam.py --modeldir=""

   
