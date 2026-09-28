# 🌱 Crop Recommendation System

## 📌 Overview

The **Crop Recommendation System** is a Machine Learning-based web application that recommends a suitable crop based on soil and environmental conditions.

The system uses a **Random Forest Classifier** trained on the Crop Recommendation dataset. Users provide information such as Nitrogen, Phosphorus, Potassium, temperature, humidity, soil pH, and rainfall. Based on these inputs, the trained model predicts a suitable crop.

The project combines **Machine Learning, Python, Flask, HTML, and CSS** to provide a simple and user-friendly crop recommendation platform.

---

## 🎯 Objectives

* To develop a Machine Learning-based crop recommendation system.
* To recommend suitable crops based on soil and environmental conditions.
* To apply the Random Forest classification algorithm to agricultural data.
* To provide a simple web interface for entering agricultural parameters.
* To demonstrate the practical application of Machine Learning in agriculture.

---

## 🚀 Features

* 🌱 Crop recommendation using Machine Learning
* 🤖 Random Forest Classifier
* 🧪 Soil nutrient analysis
* 🌡️ Temperature input
* 💧 Humidity input
* 🧑‍🌾 Soil pH input
* 🌧️ Rainfall input
* 🌐 Flask web application
* 📱 Responsive user interface
* ⚡ Fast prediction
* 🎥 Project demonstration recorded using OBS Studio

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Machine Learning

* Scikit-learn
* Random Forest Classifier

### Data Processing

* Pandas
* NumPy

### Web Development

* Flask
* HTML5
* CSS3

### Development Tools

* Visual Studio Code
* Jupyter Notebook / Python environment
* Git & GitHub
* **OBS Studio** – used for recording the project demonstration

### Dataset

* Kaggle Crop Recommendation Dataset

---

## 📊 Dataset

The project uses the **Crop Recommendation Dataset** from Kaggle.

The dataset contains the following parameters:

| Parameter     | Description                |
| ------------- | -------------------------- |
| `N`           | Nitrogen content in soil   |
| `P`           | Phosphorus content in soil |
| `K`           | Potassium content in soil  |
| `temperature` | Temperature in Celsius     |
| `humidity`    | Relative humidity          |
| `ph`          | Soil pH                    |
| `rainfall`    | Rainfall in mm             |
| `label`       | Recommended crop           |

### Dataset Format

```text
N,P,K,temperature,humidity,ph,rainfall,label
90,42,43,20.879744,82.002744,6.502985,202.935536,rice
85,58,41,21.770462,80.319644,7.038096,226.655537,rice
60,55,44,23.004459,82.320763,7.840207,263.964248,rice
```

---

## 🧠 Machine Learning Algorithm

### Random Forest Classifier

The project uses the **Random Forest Classifier** for crop prediction.

Random Forest is an ensemble learning algorithm that combines multiple decision trees to generate a prediction.

### Working Process

```text
        User Input
            ↓
   Soil & Environmental Data
            ↓
     Data Preprocessing
            ↓
   Random Forest Classifier
            ↓
      Crop Prediction
            ↓
    Recommended Crop
```

---

## 📥 Input Parameters

The user enters seven parameters:

```text
1. Nitrogen (N)
2. Phosphorus (P)
3. Potassium (K)
4. Temperature
5. Humidity
6. Soil pH
7. Rainfall
```

The values are passed to the trained Random Forest model.

---

## 📤 Output

The system displays the crop predicted by the trained Machine Learning model.

Example:

```text
Recommended Crop

🌱 Rice
```

---

## 📂 Project Structure

```text
CropRecommendation/
│
├── Crop_recommendation.csv
│
├── train_model.py
├── app.py
│
├── model/
│   └── crop_model.pkl
│
├── web_pages/
│   └── home.html
│
└── assets/
    └── style.css
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project directory

```bash
cd CropRecommendation
```

### 3. Install required libraries

```bash
pip install pandas numpy scikit-learn flask
```

---

## ▶️ How to Run

### Step 1: Train the Machine Learning Model

Run:

```bash
python train_model.py
```

This trains the Random Forest model using the dataset and creates:

```text
model/crop_model.pkl
```

---

### Step 2: Start the Flask Application

Run:

```bash
python app.py
```

The application will start at:

```text
http://127.0.0.1:5000
```

---

### Step 3: Open the Website

Open a web browser and visit:

```text
http://127.0.0.1:5000
```

---

## 🖥️ Application Workflow

```text
Start Application
       ↓
Open Web Interface
       ↓
Enter N, P, K
       ↓
Enter Temperature
       ↓
Enter Humidity
       ↓
Enter Soil pH
       ↓
Enter Rainfall
       ↓
Click "Recommend Crop"
       ↓
Flask Receives Data
       ↓
Random Forest Model
       ↓
Prediction
       ↓
Recommended Crop Displayed
```

---

## 🧪 Example Input

```text
Nitrogen       = 90
Phosphorus     = 42
Potassium      = 43
Temperature    = 20.8 °C
Humidity       = 82 %
Soil pH        = 6.5
Rainfall       = 203 mm
```

The system processes these values and returns the crop predicted by the trained model.

---

## 🎥 Project Demonstration

**OBS Studio** was used to record the demonstration of the Crop Recommendation System.

The recording demonstrates:

* Running the Flask application
* Opening the web interface
* Entering soil parameters
* Entering environmental parameters
* Generating the crop prediction
* Displaying the recommendation

---

## 🔮 Future Scope

The system can be further enhanced with:

* 🌦️ Real-time weather API integration
* 🌾 Fertilizer recommendation
* 💧 Irrigation recommendation
* 🦠 Crop disease detection
* 🗺️ Location-based recommendations
* 📊 Data visualization dashboard
* 👨‍🌾 Farmer registration and login
* 🗄️ MySQL database
* 📱 Mobile application
* 📈 Prediction history
* 🤖 Comparison of different Machine Learning algorithms

---

## ⚠️ Disclaimer

This project is developed for **educational and demonstration purposes**. Crop recommendations are based on the dataset and trained Machine Learning model used in this project. The results should not be considered a substitute for professional agricultural advice or local agronomic assessment.

---

## 👨‍💻 Author

**Manish Jaiswal**

B.Tech – Artificial Intelligence & Machine Learning

---

## ⭐ Acknowledgement

This project uses a publicly available **Crop Recommendation Dataset from Kaggle** for Machine Learning experimentation and educational purposes.

---

## 📜 License

This project is intended for educational purposes. Please check the original Kaggle dataset's license and terms before redistributing the dataset.
