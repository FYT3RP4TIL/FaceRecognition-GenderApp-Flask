# Face Recognition Web App with Machine Learning & Flask

![127 0 0 1_5000_ (1)](https://github.com/FYT3RP4TIL/FaceRecognition-GenderApp-Flask/assets/113416452/397591ac-0120-4bc5-bbc2-39adf433edea)

## :bulb: Objective :

Face recognition is a powerful technology used in various applications. This project will guide you through developing and deploying a face recognition web app using machine learning and Flask. The project will cover everything from image processing to creating a web server gateway interface.

## Project Outline :

1. **Image Processing with OpenCV**
2. **Image Data Preprocessing**
3. **Image Data Analysis (EDA)**
4. **Eigenfaces with PCA**
5. **Face Recognition Classification Model with Support Vector Machines**
6. **Pipeline Model**
7. **Flask (Jinja Template, HTML, CSS, HTTP Methods)**

Finally, we will integrate all these components to build a fully functional face recognition web app.

## 🚀&nbsp;Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/face-recognition-web-app.git
cd FaceRecognition-GenderApp-Flask
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

### 3. Activate the Virtual Environment

- On Windows:
```bash
venv\Scripts\activate
```
- On macOS and Linux:
```bash
source venv/bin/activate
```
### 4. Install Dependencies
```bash
pip install -r requirements.txt
```

### 5. Run the App
```bash
python main.py
```
Open your web browser and go to http://127.0.0.1:5000/ to see the app in action.

## Project Structure :

```yml

flaskApp/
├── templates/
│   └── index.html
├── static/
│   ├── images/
│   ├── predict/
│   └── upload/
├── model/
│   ├── model.xml
│   └── model.pickle
├── app/
│   ├── views.py
│   └── face_recognition.py
├── main.py
├── requirements.txt
├── Procfile
└── Aptfile

```

## Step-by-Step Guide

### 1. Image Processing with OpenCV
- **Load images using OpenCV.**
- **Convert images to grayscale.**
- **Resize images for uniformity.**

### 2. Image Data Preprocessing
- **Normalize image data.**
- **Flatten images for PCA.**

### 3. Image Data Analysis (EDA)
- **Visualize image data.**
- **Plot sample images.**

### 4. Eigenfaces with PCA
- **Compute Eigenfaces using PCA.**
- **Reduce dimensionality of the image data.**

### 5. Face Recognition Classification Model with SVM
- **Train SVM model using Eigenfaces.**
- **Evaluate model performance.**

### 6. Pipeline Model
- **Create a pipeline for preprocessing and classification.**
- **Save the model for deployment.**

### 7. Flask Web App
- **Create a Flask app.**
- **Render HTML templates with Jinja.**
- **Handle HTTP methods for image upload and processing.**

For Image Processing, EDA, PCA, Model Code go through [here](https://github.com/FYT3RP4TIL/ImageProcessing_EDA_SVM-Model)

## :key: Results

![127 0 0 1_5000_app_gender_ (1)](https://github.com/FYT3RP4TIL/FaceRecognition-GenderApp-Flask/assets/113416452/72122fc2-a6b0-4db5-97be-4d828e69527c)
![127 0 0 1_5000_app_gender_ (3)](https://github.com/FYT3RP4TIL/FaceRecognition-GenderApp-Flask/assets/113416452/f8f971e1-0563-4d50-b340-e11c26d4f954)
![127 0 0 1_5000_app_gender_](https://github.com/FYT3RP4TIL/FaceRecognition-GenderApp-Flask/assets/113416452/6bd8c26c-1277-4520-87ab-c3c2471cf507)
