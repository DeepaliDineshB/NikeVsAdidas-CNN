👟 NIKE vs ADIDAS Shoe Image Classification using CNN

A Deep Learning-based image classification project that identifies whether a shoe belongs to Nike or Adidas using a Convolutional Neural Network (CNN). The model preprocesses shoe images, trains on labeled datasets, and predicts the correct brand with high accuracy.

🚀 Features
CNN-based Image Classification
Automatic Image Preprocessing
Grayscale Image Conversion
Image Resizing (120 × 120)
Train & Test Dataset Preparation
Brand Prediction (Nike / Adidas)
Deep Learning Model Training
Prediction Visualization
Simple and Efficient Implementation

🛠️ Technologies Used
Python
TensorFlow
TFLearn
NumPy
Pillow (PIL)
Matplotlib
tqdm


📂 Project Structure
NIKE_vs_ADIDAS_CNN/
│
├── TRAIN/
│   ├── NIKE_*.jpg
│   └── ADIDAS_*.jpg
│
├── TEST/
│
├── train_data.npy
├── test_data.npy
├── NIKE_VS_ADIDAS_CNN.ipynb
├── requirements.txt
└── README.md


⚙️ How It Works
Load the training and testing images.
Convert images to grayscale.
Resize images to 120 × 120 pixels.
Assign labels:
Nike → [1, 0]
Adidas → [0, 1]
Train the CNN model.
Evaluate the model using test images.
Predict whether the input image is Nike or Adidas.

🧠 CNN Architecture
Input Layer
Convolution Layer (ReLU)
Max Pooling Layer
Multiple CNN Blocks
Fully Connected Layer
Dropout Layer
Softmax Output Layer

📊 Results
The trained CNN model successfully classifies shoe images into:

✅ Nike
✅ Adidas
using deep learning-based image recognition.

📈 Future Improvements
Increase dataset size
Apply Data Augmentation
Use Transfer Learning (ResNet, MobileNet, VGG16)
Improve prediction accuracy
Build a Django/Flask web application
Deploy on Render or AWS
Convert the model to TensorFlow Lite for mobile applications


👩‍💻 Author
Deepali Dinesh B
⭐ If you found this project useful, consider giving it a Star on GitHub!
