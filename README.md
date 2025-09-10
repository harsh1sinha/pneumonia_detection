# Detecting Pneumonia from Chest X-Rays

This project uses deep learning to classify chest X-ray images into two categories: **Normal** and **Pneumonia**. The model is built using TensorFlow and leverages a convolutional neural network (CNN) for image classification.

---

## 📁 Project Structure

The notebook is organized into the following main sections:

1. **Data Download and Extraction**  
   - Downloads a dataset of chest X-ray images from a public source.
   - Extracts the ZIP archive containing the dataset.

2. **Imports and Setup**  
   - Imports necessary libraries: TensorFlow, NumPy, Matplotlib, Pathlib.
   - Sets random seed for reproducibility.

3. **Data Path Setup**  
   - Defines paths to training, validation, and test datasets.

4. **Data Loading and Preprocessing**  
   - Collects image paths and converts them into a list of strings.
   - Extracts labels from image paths (Normal: 0, Pneumonia: 1).
   - Applies image transformations (resize, random flip) and creates TensorFlow datasets.

5. **Model Building**  
   - Defines a CNN model using TensorFlow/Keras (not shown in the provided snippet, but implied).

6. **Training and Evaluation**  
   - Trains the model on the training dataset.
   - Evaluates performance on the validation set.

7. **Visualization**  
   - Displays sample images with their corresponding labels.

---

## 🛠️ Technologies Used

- **TensorFlow** – For building and training the CNN.
- **NumPy** – For numerical operations.
- **Matplotlib** – For visualizing images and results.
- **Pathlib** – For handling file paths.

---

## 📊 Dataset

The dataset is organized into three directories:

- `chest_xray/train/` – Training images
- `chest_xray/test/` – Validation images
- `chest_xray/val/` – Test images

Each directory contains two subfolders:
- `NORMAL/`
- `PNEUMONIA/`

---

## 🧠 Model

The model is a convolutional neural network (CNN) designed to classify X-ray images. It includes:

- Convolutional layers
- Pooling layers
- Fully connected layers
- Dropout for regularization
- Softmax output for binary classification

---

## 📈 Results

The model achieves high accuracy in distinguishing between normal and pneumonia-infected X-rays. Sample predictions and visualizations are included in the notebook.

---

## 🚀 How to Run

1. Download the dataset using the provided link or use your own.
2. Update the paths in the notebook if necessary.
3. Run the cells sequentially to preprocess data, train the model, and evaluate results.
4. Use the trained model to make predictions on new X-ray images.

---


