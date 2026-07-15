# 👟 Nike vs Adidas Shoe Image Classification using CNN

A Deep Learning project that classifies shoe images as **Nike** or **Adidas** using a **Convolutional Neural Network (CNN)** built with **TensorFlow/Keras**. The model preprocesses images by converting them to grayscale, resizing them, and then learns image features to accurately predict the shoe brand.

---

# 🚀 Features

- CNN-based image classification
- Automatic image preprocessing
- Grayscale image conversion
- Image resizing (120 × 120 pixels)
- One-hot encoded class labels
- Deep learning model training using TensorFlow/Keras
- Brand prediction for new shoe images
- Simple and efficient implementation

---

# 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pillow (PIL)
- Matplotlib
- tqdm

---

# 📂 Project Structure

```text
NIKE_vs_ADIDAS_CNN/
│
├── train/
│   ├── NIKE_1.jpg
│   ├── NIKE_2.jpg
│   ├── ADIDAS_1.jpg
│   └── ...
│
├── test/
│   ├── NIKE_101.jpg
│   ├── ADIDAS_102.jpg
│   └── ...
│
├── NIKE_VS_ADIDAS_CNN.ipynb
├── requirements.txt
└── README.md
```

---

# ⚙️ How It Works

1. Load the training and testing images.
2. Convert each image to grayscale.
3. Resize images to **120 × 120** pixels.
4. Assign labels using one-hot encoding:
   - Nike → **[1, 0]**
   - Adidas → **[0, 1]**
5. Normalize pixel values to the range **0–1**.
6. Train the CNN model.
7. Predict whether a new shoe image belongs to **Nike** or **Adidas**.

---

# 🧠 CNN Architecture

- Input Layer (120 × 120 × 1)
- Conv2D (16 filters, 3×3, ReLU)
- Conv2D (32 filters, 5×5, ReLU)
- MaxPooling2D (2×2)
- Conv2D (32 filters, 3×3, ReLU)
- MaxPooling2D (2×2)
- Conv2D (64 filters, 3×3, ReLU)
- MaxPooling2D (2×2)
- Flatten Layer
- Dense Layer (64 neurons, ReLU)
- Dropout (0.2)
- Output Layer (2 neurons, Softmax)

---

# 📊 Model Performance

- **Optimizer:** Adam
- **Loss Function:** Categorical Crossentropy
- **Evaluation Metric:** Accuracy
- **Training Epochs:** 10
- **Training Accuracy:** Approximately **94%**

---

# ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/NIKE_vs_ADIDAS_CNN.git
cd NIKE_vs_ADIDAS_CNN
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Project

Open the notebook in **Google Colab** or **Jupyter Notebook** and run all the cells.

```bash
NIKE_VS_ADIDAS_CNN.ipynb
```

To test the model:
- Place the input shoe image in the project directory.
- Update the image path in the prediction cell.
- Run the notebook to predict whether the shoe is **Nike** or **Adidas**.

---

# 📈 Future Improvements

- Increase the dataset size.
- Apply data augmentation techniques.
- Use transfer learning models such as **MobileNetV2**, **ResNet50**, or **VGG16**.
- Improve classification accuracy.
- Develop a web application using **Django** or **Flask**.
- Deploy the model on **Render** or **AWS**.
- Convert the model to **TensorFlow Lite** for mobile deployment.

---

# 👩‍💻 Author

**Deepali Dinesh B**

Aspiring Software Engineer | Machine Learning & Deep Learning Enthusiast

---

# ⭐ Support

If you found this project helpful, please consider giving it a **Star ⭐** on GitHub.
- TensorFlow
- TFLearn
- NumPy
- Pillow (PIL)
- Matplotlib
- tqdm

---

## 📂 Project Structure

```text
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
```

---

## ⚙️ How It Works

1. Load the training and testing images.
2. Convert images to grayscale.
3. Resize images to **120 × 120** pixels.
4. Assign labels:
   - Nike → `[1, 0]`
   - Adidas → `[0, 1]`
5. Train the CNN model.
6. Evaluate the model using test images.
7. Predict whether the input image is **Nike** or **Adidas**.

---

## 🧠 CNN Architecture

- Input Layer
- Convolution Layer (ReLU)
- Max Pooling Layer
- Multiple CNN Blocks
- Fully Connected Layer
- Dropout Layer
- Softmax Output Layer

---

## 📊 Results

The trained CNN model successfully classifies shoe images into:

- ✅ Nike
- ✅ Adidas

using deep learning-based image recognition.

---

## 📈 Future Improvements

- Increase dataset size
- Apply Data Augmentation
- Use Transfer Learning (ResNet, MobileNet, VGG16)
- Improve prediction accuracy
- Build a Django/Flask web application
- Deploy on Render or AWS
- Convert the model to TensorFlow Lite for mobile applications

---

## 👩‍💻 Author

**Deepali Dinesh B**

⭐ If you found this project useful, consider giving it a **Star** on GitHub!
