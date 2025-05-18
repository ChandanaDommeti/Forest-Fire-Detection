Here’s a professional and well-structured **README.md** content for your wildfire detection project:

---

# 🔥 Forest Fire Detection Using Deep Learning

## 📌 Project Overview

This project aims to detect wildfires from forest images using a Convolutional Neural Network (CNN). By classifying images as either “fire” or “no fire,” the model assists in early detection of wildfires—an essential step for minimizing environmental damage and ensuring rapid emergency response.

---

## 🎯 Objectives

* Build an image classification model using CNN.
* Learn and apply preprocessing techniques on image datasets.
* Use data augmentation and dropout to prevent overfitting.
* Evaluate model performance using accuracy, loss curves, and confusion matrix.
* Test model on unseen data and build a prediction script for new inputs.
* Lay the groundwork for real-time fire detection applications.

---

## 🛠️ Tools & Technologies

* **Python** – Core programming language.
* **TensorFlow & Keras** – Model development and training.
* **OpenCV** – Image processing and handling.
* **NumPy & Pandas** – Data manipulation.
* **Matplotlib & Seaborn** – Visualization and plotting.
* **Scikit-learn** – Evaluation metrics and utilities.
* **Google Colab / Jupyter Notebook** – Development environment.
* **Kaggle** – Dataset source.
* **Gradio / Streamlit (Planned)** – UI for live image classification demo.

---

## 📁 Dataset

* **Source**: [Kaggle – The Wildfire Dataset](https://www.kaggle.com/datasets/elmadafri/the-wildfire-dataset)
* **Classes**: `fire`, `nofire`
* **Split**: Training, Validation, and Test sets

---

## 🧠 Model Architecture

* **Input Layer**: 150x150 image size
* **Convolutional Layers**: Feature extraction
* **MaxPooling Layers**: Downsampling
* **Dropout Layers**: Regularization
* **Dense Layers**: Classification
* **Output**: Sigmoid activation for binary classification

---

## 📈 Model Performance

* **Training Accuracy**: \~93% (best epoch)
* **Validation Accuracy**: \~83%
* **Test Accuracy**: \~83%
* **Loss**: Reduced consistently after each epoch

---

## 🚀 How to Use

1. Clone the repository:

   ```bash
   git clone (https://github.com/ChandanaDommeti/Forest-Fire-Detection)
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the prediction:

   ```python
   python predict.py --img_path path/to/image.jpg
   ```

---

## 🧪 Example Prediction

```python
predict_fire("test/nofire/sample.jpg")
# Output: Predicted - No Fire
```

---

## 🔍 Future Scope

* Real-time detection from live video feeds or drone footage
* Integration with mobile/web apps
* Use of transfer learning to improve accuracy on smaller datasets
* Deployment on cloud platforms for scalability

---

## 👨‍💻 Author

**Dommeti Chandana**
B.Tech CSE (AI & ML)
Shell-Edunet Skill4Future AICTE Internship Project

---

