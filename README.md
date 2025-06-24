Plant Disease Classification using CNN
This project implements a Convolutional Neural Network (CNN) to classify plant diseases using an augmented image dataset. The model is trained using TensorFlow and Keras.

📂 Dataset
The dataset used is the New Plant Diseases Dataset (Augmented), structured into training and validation directories. The dataset should be organized as:
dataset/
├── train/
│   ├── class_1/
│   ├── class_2/
│   └── ...
└── valid/
    ├── class_1/
    ├── class_2/
    └── ...
    
🧠 Model Architecture
The CNN model includes several convolutional, max-pooling, and dropout layers. The architecture increases filter sizes in deeper layers to improve feature extraction:
Input shape: (128, 128, 3)
Multiple Conv2D + ReLU layers
MaxPooling2D layers
Final Dense layer(s) with softmax activation for classification

🛠️ Technologies Used
Python
TensorFlow / Keras
Matplotlib, Seaborn (for visualization)
Pandas

🚀 How to Run
Clone the repository.
Install dependencies:
pip install tensorflow matplotlib pandas seaborn
Ensure dataset is properly structured and update paths if needed.
Run the notebook:
jupyter notebook Train.ipynb

📈 Outputs
Model accuracy and loss plots
Layer-wise architecture summary
Evaluation metrics on validation data

📌 Notes
Uses image_dataset_from_directory with label_mode="categorical"
Designed for multi-class classification
Dataset must be downloaded manually due to size

📜 License
MIT License (or update as applicable)
