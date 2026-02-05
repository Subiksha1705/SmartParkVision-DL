# SmartParkVision-DL

SmartParkVision-DL is a deep learning mini project that focuses on detecting parking space occupancy using computer vision.  
The model analyzes parking lot images and classifies parking slots as occupied or vacant.

This project is intended for learning and understanding deep learning concepts through a real-world image classification problem.

---

## Project Goal

- Apply deep learning to computer vision tasks
- Detect occupied and vacant parking spaces from images
- Work with real-world parking datasets
- Understand the end-to-end deep learning workflow

---

## Algorithm Used

This project uses a Convolutional Neural Network (CNN) for parking space occupancy detection.

CNNs automatically learn visual features such as edges, textures, and object shapes directly from images, making them suitable for image classification tasks.

### Working Principle

1. Parking lot images are given as input.
2. Images are resized and normalized during preprocessing.
3. Convolution layers extract visual features like vehicle edges and shapes.
4. Pooling layers reduce dimensionality and computation.
5. Fully connected layers perform classification.
6. The output predicts whether a parking slot is occupied or vacant.

---

## Training Details

- Model Type: Convolutional Neural Network (CNN)
- Loss Function: Binary Cross-Entropy
- Optimizer: Adam
- Evaluation Metric: Accuracy
- Overfitting Control: Early Stopping

---

## Dataset

- Parking space images labeled as occupied or vacant
- Includes real-world variations such as:
  - Day and night images
  - Shadows and lighting conditions
  - Different camera perspectives

---

## Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

---

## How to Run

1. Clone the repository:
   git clone https://github.com/<your-username>/SmartParkVision-DL.git

2. Navigate to the project folder:
   cd SmartParkVision-DL

3. Install required dependencies:
   pip install -r requirements.txt

4. Open the notebook:
   jupyter notebook

5. Run the cells sequentially.

---

## Output

- Classifies parking spaces as occupied or vacant
- Displays training accuracy and loss curves

---

## Learning Outcomes

- Practical understanding of CNN-based image classification
- Experience with dataset preprocessing and model training
- Exposure to real-world computer vision challenges

---

## Notes

- This is a deep learning mini project
- Created for academic learning and practice

---

## Author

Subiksha R
