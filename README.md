# Blind Assistance System

## Overview

The **Blind Assistance System** is an assistive navigation tool designed to help visually impaired individuals navigate their surroundings safely and independently. Leveraging advanced computer vision techniques, the system provides real-time object detection and distance estimation with high accuracy. Built using Python, Midas, and TensorFlow, this project aims to empower users by offering a reliable and intuitive way to perceive their environment.

## Key Features

- **Object Detection**: Achieves **93% accuracy** in detecting objects in the user's surroundings.
- **Distance Estimation**: Implements a bounding box algorithm to measure the distance between the user and objects within a range of **3-10 meters**.
- **Depth Estimation**: Utilizes **molecular depth estimation** to analyze images, estimating object distances with an error margin of **less than 5%**.
- **Real-Time Feedback**: Provides real-time auditory or haptic feedback to guide users around obstacles.

## Technologies Used

- **Python**: The core programming language used for development.
- **Midas**: A deep learning model for depth estimation, enabling accurate distance measurement.
- **TensorFlow**: Used for implementing and training the object detection model.
- **OpenCV**: For image processing and real-time video feed handling.

## How It Works

1. **Object Detection**: The system uses a pre-trained TensorFlow model to detect objects in the user's environment. The model identifies objects and draws bounding boxes around them.
2. **Distance Estimation**: A custom bounding box algorithm calculates the distance between the user and the detected objects. This is achieved by analyzing the size and position of the bounding boxes in the image.
3. **Depth Estimation**: The Midas model is employed to estimate the depth of the scene, providing additional accuracy to the distance measurements.
4. **Feedback Mechanism**: The system provides real-time feedback to the user through auditory cues or vibrations, helping them navigate around obstacles.

## Performance Metrics

- **Object Detection Accuracy**: **93%**
- **Distance Estimation Range**: **3-10 meters**
- **Depth Estimation Error Margin**: **< 5%**

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/blind-assistance-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd blind-assistance-system
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the system:
   ```bash
   python main.py
   ```

## Usage

1. Ensure your camera is connected and properly configured.
2. Run the system using the command above.
3. The system will start detecting objects and estimating distances in real-time.
4. Follow the auditory or haptic feedback to navigate around obstacles.

## Future Enhancements

- **Integration with Wearable Devices**: To make the system more portable and user-friendly.
- **Improved Feedback Mechanisms**: Adding more intuitive feedback options, such as voice commands or detailed audio descriptions.
- **Expanded Object Detection Capabilities**: Training the model to recognize a wider variety of objects and scenarios.

## Contributing

We welcome contributions to the Blind Assistance System! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push to your branch.
4. Submit a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- Thanks to the developers of Midas and TensorFlow for their powerful tools and libraries.
- Special thanks to the open-source community for their continuous support and contributions.

## Contact

For any questions or feedback, please reach out to:


- **Email**: aayushaayush107@gmail.com


---

**Blind Assistance System** is a step toward creating a more inclusive world for visually impaired individuals. Your feedback and contributions are highly appreciated!
