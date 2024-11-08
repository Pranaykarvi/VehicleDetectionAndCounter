# Vehicle Detection and Counter

This project uses the YOLO V8 model to detect and count vehicles in a video feed. The system labels each vehicle and provides a real-time count, making it useful for traffic monitoring and surveillance applications.

![Vehicle Detection Screenshot](MainImp/Screenshot%202024-11-08%20103929.png)

*Example output showing vehicle detection and counting in real-time.*

## Features
- Real-time vehicle detection using YOLO V8
- Labeling of detected vehicles
- Count of vehicles in the frame
- Process video input (can be from a file or webcam)

## Installation

### Prerequisites
Ensure that you have Python 3.7 or higher installed. This project requires several libraries that can be installed via `pip`.

### Steps
1. **Clone the repository:**

   ```bash
   git clone https://github.com/Pranaykarvi/VehicleDetectionAndCounter.git
   cd VehicleDetectionAndCounter
2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
## Sample Video
Here’s an example of how the vehicle detection looks on a sample video.

[![Vehicle Detection Demo](https://img.youtube.com/vi/_vAlCp5KdWs/0.jpg)](https://youtu.be/_vAlCp5KdWs)
## Model Training
To train the YOLO V8 model on custom data, you need to prepare a dataset in the YOLO format. You can use tools like LabelImg to annotate your dataset.

- After preparing the dataset, modify the `config.yaml` file to point to the custom data.
- Start the training process by following the YOLO training instructions.
- Save your trained weights in the `models` directory.

## Dependencies
This project relies on the following Python packages:
- OpenCV
- Numpy
- TensorFlow/PyTorch (depending on your model configuration)
- other necessary dependencies listed in `requirements.txt`

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
