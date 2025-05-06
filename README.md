# ksl-tranlator
An AI-powered Korean Sign Language (KSL) recognition system using computer vision and deep learning. This project processes video input to detect and classify KSL gestures in real time, with the goal of enhancing accessibility for the Deaf and hard-of-hearing community. Built with Python, OpenCV, and TensorFlow.

## Features
- Real-time video capture and gesture detection
- Keypoint extraction using MediaPipe / OpenCV
- Sign classification using a deep learning model (TensorFlow/Keras)
- Scalable design for future integration with web/mobile platforms
- Custom dataset support for KSL signs

## Tech Stack
- Python
- OpenCV
- MediaPipe (or equivalent keypoint detection)
- TensorFlow / Keras
- NumPy, Pandas

## Demo
*Coming soon:* A demo video showcasing real-time KSL gesture detection and classification.

## Getting Started

### Prerequisites
- Python 3.7+
- pip

### Installation
Clone the repository:
```bash
git clone https://github.com/yourusername/ksl-recognition.git
cd ksl-recognition
```

Install dependencies:
```bash
pip install -r requirements.txt
```

### Running the App
To start real-time gesture recognition:
```bash
python main.py
```

## Dataset
Custom dataset collected from video recordings of KSL gestures. You can replace or augment the dataset under the `/data` folder.

## Folder Structure
```
/data          - KSL video/image dataset  
/models        - Trained model weights  
/scripts       - Training, preprocessing, and utility scripts  
main.py        - Main application script for real-time recognition  
README.md      - Project documentation  
```

## Future Plans
- Expand dataset to cover more signs
- Improve accuracy with CNN-LSTM or transformer-based models
- Build web/mobile app integration
- Prepare for open-source deployment and research publication

## License
MIT License

## Acknowledgments
- Inspired by accessibility goals for the Deaf and hard-of-hearing
- Initial research support aligned with the Fulbright U.S.-Korea STEM initiative
