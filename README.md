# MSc Final Project: License Plate Detection and Recognition with YOLOv11 🚗🔍

Welcome to the **License Plate Detection and Recognition** project for my MSc Final Project. This repository showcases the development of an **Automatic License Plate Recognition (ALPR) system**, leveraging the YOLOv11 object detection framework and Optical Character Recognition (OCR) methods to identify and interpret license plates in various scenarios. 🎓

---

## 🌐 Project Objectives

1. **License Plate Detection**:
   - Deploy YOLOv11 to detect license plates in challenging environments (e.g., poor lighting, angles, occlusions).
   
2. **Character Recognition**:
   - Apply OCR methods to read the detected license plates accurately.

3. **Enhancing Detection Accuracy**:
   - Incorporate preprocessing techniques like noise reduction and bounding box optimization to improve YOLOv11’s efficiency.

4. **Pipeline Integration**:
   - Build a unified system for real-world license plate recognition.

---

## 📁 Repository Structure

- **`notebooks/Yolo_CNN_tesseract.ipynb`**: Jupyter Notebook demonstrating YOLOv11-based detection and OCR integration.
- **`data/`**: Includes training, validation, and test datasets for model development.
- **`models/`**: Pretrained YOLOv11 model weights and configuration files.
- **`reports/`**:
  - `Literature Review.pdf`: A detailed review of research on ALPR systems.
  - `Methodology.pdf`: Overview of techniques employed in the project.
  - `Final Report.pdf`: Comprehensive explanation of the project findings and results.
- **`requirements.txt`**: Dependencies required to execute the project code.
- **`results/`**: Visualizations of model predictions and evaluation metrics.

---

## 🔧 Installation and Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/pp23aai/MSc-Final-project--2024-25.git
   cd MSc-Final-project--2024-25
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

 
---

## 🚀 Usage

### 1. Data Preprocessing
   - Use the notebook to visualize and preprocess the dataset, ensuring it is optimized for YOLOv11.

### 2. Training the YOLOv11 Model
   - Train the model using the prepared dataset:
     ```bash
     python src/train.py --model yolov11 --data data/dataset.yaml
     ```

### 3. Evaluating Results
   - Evaluate model performance and visualize detection results:
     ```bash
     python src/evaluate.py --model yolov11 --test data/test/
     ```

### 4. Running OCR for Character Recognition
   - Integrate OCR to read text from detected license plates.

---

## 🧩 Key Features

1. **YOLOv11-Based Detection**:
   - Implements YOLOv11 for detecting license plates in diverse scenarios.

2. **Advanced Preprocessing**:
   - Includes noise reduction, contrast enhancement, and bounding box visualization.

3. **OCR Integration**:
   - Extracts text from detected plates using OCR for accurate character recognition.

4. **Exploratory Analysis**:
   - Visualizes dataset statistics like class distributions and bounding box dimensions.

---

## 📊 Results

- **Detection Accuracy**:
  - The YOLOv11 model demonstrated high accuracy in detecting license plates under various conditions.
  
- **Character Recognition**:
  - Preliminary OCR results indicate promising performance in accurately reading license plate text.
  
- **Key Findings**:
  - Incorporating preprocessing techniques improved detection accuracy significantly.

---

## 🔮 Future Work

- **Real-Time Processing**:
  - Implement live detection from video streams for traffic monitoring.

- **Dataset Expansion**:
  - Include more diverse datasets to enhance generalization capabilities.

- **Advanced OCR Techniques**:
  - Test state-of-the-art OCR models to boost recognition accuracy.

---

## 🙏 Acknowledgments

Special thanks to:
- [Ultralytics](https://ultralytics.com/) for the YOLO framework.
- [Roboflow](https://roboflow.com/) for providing datasets.
- MSc mentor ( Vandana Das ) and colleagues for their guidance and support throughout this project.

 

 
