# License Plate Detection with YOLOv11 🚗🔍

Welcome to the GitHub repository for my MSc Final Project on **License Plate Detection**! 🎓 This project explores various preprocessing techniques and deep learning models to enhance the accuracy and efficiency of license plate detection and character recognition. The project’s primary focus is using YOLOv11 for the detection phase, while incorporating insights from state-of-the-art cNN VS OCR models for character recognition. 🤖📝

## Project Overview 🌐

Automatic License Plate Recognition (ALPR) systems have become essential in areas such as traffic management, law enforcement, and security. 🚓🚦 This project investigates techniques to improve license plate detection, primarily by implementing YOLOv11 and experimenting with different preprocessing methods to increase model performance.

## Objectives 🎯

1. **License Plate Detection**: Using YOLOv11, a robust object detection model, to localize license plates in real-world images.
2. **Preprocessing Techniques**: Exploring preprocessing steps, such as noise reduction, contrast enhancement, and edge detection, to optimize detection and recognition.
3. **Character Recognition**: Applying Optical Character Recognition (OCR) techniques to read the detected license plates accurately.

## Project Structure 📁

- `Project Management plan `: Contains information about project and timelines
- `data/`: Contains datasets used for training and evaluation, sourced from [Roboflow](https://roboflow.com).
- `models/`: YOLOv11 and OCR model weights and configuration files.
- `notebooks/Yolo/results`: Jupyter notebooks for exploratory data analysis, training, and evaluation.
- ` 

## Key Components 🧩

### 1. Preprocessing Techniques ⚙️
To enhance detection and recognition accuracy, this project tests several preprocessing techniques, including:
    
### 2. YOLOv11 for License Plate Detection 🛣️
YOLOv11 is employed to detect license plates in various conditions, addressing challenges such as different lighting, angles, and occlusions.

### 3. CNN and  Optical Character Recognition (OCR) 📝
Using OCR models to recognize and extract text from detected license plates, improving the reliability of license plate reading.

## Installation 🛠️

To set up the environment, clone the repository and install dependencies:

```bash
git clone https://github.com/pp23aai/MSc-Final-project--2024-25.git
cd MSc-Final-project--2024-25
pip install -r requirements.txt
```

## Usage 💻

1. **Data Preprocessing**: Run preprocessing scripts to prepare the dataset.
2. **Training**: Use YOLOv11 for license plate detection training.
3. **Evaluation**: Evaluate model performance with test data and OCR accuracy.

```bash
python src/train.py --model yolov11 --data data/dataset.yaml
```

## Results 📊

Initial results show significant improvements in detection accuracy by using advanced preprocessing techniques and the YOLOv11 model for plate localization. Further analysis is ongoing to refine OCR accuracy. 📈

## Future Work 🚀

- Integrating real-time detection for live video streams. 🎥
- Expanding dataset diversity for better generalization. 🌍
- Experimenting with alternative OCR methods to improve character recognition accuracy. 🧠

## Acknowledgments 🙏

This project uses datasets from [Roboflow](https://roboflow.com) and resources from the MSc course module. Special thanks to my mentors and peers for their support throughout this project. 🌟

 
