# Mask Detection Using Webcam

This project utilizes a YOLO model to detect whether individuals are wearing masks using a webcam feed.

## Prerequisites

- Python 3.x
- OpenCV
- Ultralytics YOLO (ensure you have the correct version installed)

## Installation

1. **Clone the repository** (if applicable):
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install required packages**:
   You can install the necessary packages using pip:
   ```bash
   pip install opencv-python
   pip install ultralytics
   ```

3. **Download the Dataset**:
   You can download the dataset from Kaggle:
   [Face Mask Detection Dataset](https://www.kaggle.com/datasets/andrewmvd/face-mask-detection)
   
   Ensure you have the dataset downloaded and structured correctly. Place it in the following directory:
   ```
   /Users/chakriyedluri/Downloads/archive/
   ```

4. **Download the YOLO Weights**:
   Make sure you have the YOLO weights file (e.g., `best_local.pt`) in the same directory.

## Execution

1. **Run the Mask Detection Script**:
   Execute the following command in your terminal:
   ```bash
   python mask_detection_using_webcam.py
   ```

2. **Using the Webcam**:
   The script will open a window displaying the webcam feed. It will detect faces and indicate whether they are wearing masks or not.

3. **Exit the Program**:
   To stop the webcam feed, press the 'q' key.

## Notes

- Ensure your webcam is connected and accessible.
- Adjust the model path in the script if necessary to point to your YOLO weights.
