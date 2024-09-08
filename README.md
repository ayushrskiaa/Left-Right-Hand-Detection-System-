

# Left-Right Hand Detection System

This project implements a real-time hand detection system using **OpenCV** and **MediaPipe**. The system processes video input from a webcam to classify hands as either left or right. It utilizes hand landmark recognition and image processing techniques to achieve accurate detection. The system can recognize both hands simultaneously and display labels ("Left Hand" or "Right Hand") on the video feed in real time.

## Features

- **Real-time Hand Detection**: Captures and processes video input from the webcam.
- **Left and Right Hand Classification**: Uses MediaPipe's hand landmark model to differentiate between left and right hands.
- **Simultaneous Hand Detection**: Supports detection of both hands at once.
- **On-Screen Labels**: Displays "Left Hand" or "Right Hand" directly on the video feed, indicating which hand is detected.

## Tech Stack

- **Python**: Main programming language used for the project.
- **OpenCV**: Library for real-time image and video processing.
- **MediaPipe**: Hand tracking and landmark detection framework.
- **Google Protobuf**: Used to handle the message data for classification.

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/left-right-hand-detection.git
   ```

2. Navigate to the project directory:
   ```bash
   cd left-right-hand-detection
   ```

3. Install the required dependencies:
   ```bash
   pip install opencv-python mediapipe protobuf
   ```

4. Run the script:
   ```bash
   python hand_detection.py
   ```

5. The system will start capturing video from your webcam and display the detected hand labels in real time.

## Usage

- **Real-time Classification**: The system will classify each hand detected as "Left Hand" or "Right Hand."
- **Simultaneous Hand Detection**: When both hands are detected, it will display "Both Hands."
- Press `q` to quit the program.

## Future Enhancements

- Implement gesture recognition for more advanced hand-tracking features.
- Add support for more robust hand detection in low-light conditions.
- Explore performance optimization for smoother real-time processing.

## License

This project is licensed under the MIT License.

