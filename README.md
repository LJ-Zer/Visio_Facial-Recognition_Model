# INSIDE THE FOLDER EXECUTE THIS IN TERMINAL.

## Preparation

1. Install Anaconda
    *Create Virtual Environment
      **conda create --name inference python=3.9
2. Activate the Environment
      **conda activate automatic
3. Install Dependencies
      **pip install tensorflow opencv-python protobuf==3.20

## Inferencing 

1. Activate the Environment
      ** conda activate inference
2. Run the Python for Real-time Dataset Fetcher
    *Run the script in Auto-Face directory. Make sure to change the imagedir.
      **python TFLite_detection_webcam.py --modeldir=""

   
