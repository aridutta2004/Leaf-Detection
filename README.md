# 🌿 Plant Disease Classification using CNN

This project implements a Convolutional Neural Network (CNN) to classify plant diseases using an augmented image dataset. The model is trained using TensorFlow and Keras.

---

## 📂 Dataset

The dataset used is the **New Plant Diseases Dataset (Augmented)**, structured into training and validation directories. The directory structure should look like this:

```
dataset/
├── train/
│   ├── class_1/
│   ├── class_2/
│   └── ...
└── valid/
    ├── class_1/
    ├── class_2/
    └── ...
```

---

## 🧠 Model Architecture

The CNN model includes multiple convolutional, max-pooling, and dropout layers. The architecture increases filter sizes in deeper layers to improve feature extraction.

- **Input shape:** `(128, 128, 3)`
- **Convolutional layers:** with ReLU activation
- **MaxPooling2D layers**
- **Dropout layers**
- **Final Dense layer:** with softmax activation for multi-class classification

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- Matplotlib, Seaborn (for visualization)
- Pandas

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/aridutta2004/Leaf-Detection.git
cd Leaf-Detection

# Install dependencies
pip install tensorflow matplotlib pandas seaborn

# Run the notebook
jupyter notebook Train.ipynb
```

---

## 📈 Outputs

- Model training accuracy and loss plots
- CNN architecture summary
- Evaluation metrics on validation data

---

## 📌 Notes

- Uses `image_dataset_from_directory` with `label_mode="categorical"`
- Designed for multi-class image classification
- Dataset must be downloaded manually due to its size

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
