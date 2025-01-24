# Hand Bone Fracture Detection in X-Ray Images Using Hybrid YOLO V8

This project leverages YOLO V8, an advanced object detection model, to detect hand bone fractures from X-ray images. The model is trained on a dataset of 1200 hand-bone X-ray images classified into six fracture categories, offering improved accuracy and speed compared to YOLO NAS.

## Features
- **YOLO V8 Model**: Uses the latest version of YOLO for improved real-time object detection, tailored for medical image analysis.
- **Accurate Detection**: Detects both subtle and complex fractures, improving diagnostic accuracy in clinical settings.
- **Efficient Performance**: Enhanced speed and efficiency, ensuring faster diagnoses for timely medical intervention.

## Technologies Used
- **YOLO V8**: Deep learning framework for object detection.
- **Python**: Programming language used for training and evaluation.
- **OpenCV, NumPy**: Libraries used for image preprocessing and model evaluation.
- **TensorFlow/Keras**: Frameworks used for model development and training.

## Installation

Follow these steps to set up the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/Akhil1409906/hand-bone-fracture-detection.git
2. Navigate to the project directory:
    cd hand-bone-fracture-detection
   
3. Install the required dependencies:
   pip install -r requirements.txt
   
4. Run the model training script:
   python train_model.py
   
5. Evaluate the model:
   python evaluate_model.py

