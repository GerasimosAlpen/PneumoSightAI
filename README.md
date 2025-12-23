## 📌 Overview
PneumoSight is an Artificial Intelligence based system that proposes a solution for the early detection of pneumonia using Chest X-Ray images. This AI system based on a Convolutional Neural Network (CNN) algorithm to automatically classify lung X-ray images into Normal and Pneumonia categories as an early diagnostic support tool for healthcare professionals.

## ✨ Features
- Automatic classification of Chest X-Ray images into Normal and Pneumonia categories
- Display of classification accuracy percentage to represent model performance

## ⚙️ Technologies Used
Frontend
- React

Backend
- Python
- Flask
- Flask-CORS
- TensorFlow & Keras — loading and running the AI model
- NumPy & OpenCV — image preprocessing

AI Training
- NumPy, Pandas — data manipulation and analysis
- Matplotlib, Seaborn — training data visualization
- Scikit-learn — dataset splitting and model evaluation
- TensorFlow & Keras — CNN model training
- OpenCV — image preprocessing and data augmentation

## 🚀 Installation
If you want to run this project locally, follow these steps :
1. Clone the repository
```
git <span style="color: orange;">orange</span> https://github.com/GerasimosAlpen/PneumoSightAI.git
```
3. Navigate to the project directory:
```
<span style="color: orange;">cd</span> PneumoSightAI
```

Client setup : 
1. Navigate to the client directory :
```
<span style="color: orange;">cd</span> Client
```
2. Install dependencies :
```
npm install
```
3. Start the development server :
```
npm run dev
```
4. Open the following URL in your browser :
```
http://localhost:5173
```

Server setup : 
1. Navigate to the server directory :
```
<span style="color: orange;">cd</span> Server
```
2. Install required dependencies :
```
pip install -r requirements.txt
```
3. Run the server :
```
python app.py
```
4. The backend server will run at:
```
http://localhost:5000
```



