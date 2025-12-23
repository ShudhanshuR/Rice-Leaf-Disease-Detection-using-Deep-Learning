🌾 Rice Leaf Disease Detection using Deep Learning
📌 Project Overview

Rice is one of the most important crops worldwide. Leaf diseases directly affect crop yield and farmer income.
This project uses Deep Learning with TensorFlow to automatically detect rice leaf diseases from images.

The model classifies rice leaves into three disease categories using a Convolutional Neural Network (CNN).

🎯 Objectives

Detect rice leaf diseases from images

Reduce dependency on manual inspection

Improve early disease identification

Provide a scalable AI-based solution for agriculture

🦠 Disease Classes

The model predicts the following classes:

Bacterial Leaf Blight

Brown Spot

Leaf Smut

🧠 Technology Stack

Programming Language: Python

Framework: TensorFlow & Keras

IDE: Jupyter Notebook

Libraries: NumPy, Matplotlib, OpenCV

Model Type: Convolutional Neural Network (CNN)

📂 Project Structure
CAPSTONE/
│
├── Rice Leaf Disease Detection/
│   ├── train/
│   │   ├── Bacterial leaf blight/
│   │   ├── Brown spot/
│   │   └── Leaf smut/
│   │
│   ├── val/
│   │   ├── Bacterial leaf blight/
│   │   ├── Brown spot/
│   │   └── Leaf smut/
│   │
│   ├── Rice_Leaf_Disease_Detection.ipynb
│   ├── best_rice_leaf_model.h5
│   └── README.md

⚙️ How to Run the Project
1️⃣ Install Required Libraries
pip install tensorflow numpy matplotlib opencv-python

2️⃣ Open Jupyter Notebook
jupyter notebook


Open:

Rice_Leaf_Disease_Detection.ipynb

3️⃣ Train the Model

Run all cells to:

Load images

Train CNN model

Validate accuracy

4️⃣ Test on New Image

Download any rice leaf image and give its path:

img_path = "/Users/YourName/Downloads/test_leaf.jpg"


The model will predict:

Disease name

Confidence score

📊 Model Performance

Training Accuracy: ~85–90%

Validation Accuracy: ~83%

Performs well on clear and properly captured images

⚠️ Project Risks

Limited dataset size

Image quality dependency

Lighting and background variation

Overfitting on training data

Hardware dependency for training

🚀 Future Improvements

Increase dataset size

Add more rice disease classes

Use transfer learning (ResNet, EfficientNet)

Deploy as a web or mobile application

Real-time disease detection using camera

🧪 Use Case

Farmers

Agricultural experts

Smart farming systems

Research and academic projects

🏁 Conclusion

This project demonstrates the power of deep learning in agriculture.
By automating rice leaf disease detection, it helps in early diagnosis, reduces crop loss, and supports smart farming initiatives.

👨‍💻 Author

Shudhanshu Ranjan


