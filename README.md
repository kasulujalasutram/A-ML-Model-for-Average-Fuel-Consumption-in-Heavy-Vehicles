
# 🚛 Average Fuel Consumption Prediction Using Machine Learning

A GUI-based Machine Learning application that predicts the average fuel consumption of heavy vehicles using an Artificial Neural Network (ANN). The application is built with Python, Tkinter, Scikit-learn, and Keras.

## 📌 Project Overview

Fuel consumption is a critical factor in transportation and logistics. This project uses Machine Learning techniques to predict the average fuel consumption of heavy vehicles based on vehicle-related attributes.

The system provides a user-friendly graphical interface where users can:

- Upload a vehicle dataset
- Train an Artificial Neural Network (ANN)
- Evaluate model accuracy
- Predict fuel consumption for new vehicle data
- Visualize prediction results through graphs

---

## ✨ Features

- Graphical User Interface (GUI) using Tkinter
- Dataset upload functionality
- Automatic dataset preprocessing
- One-Hot Encoding for output labels
- Artificial Neural Network (ANN) model
- Fuel consumption prediction
- Accuracy evaluation
- Data visualization using Matplotlib

---

## 🛠️ Technologies Used

- Python
- Tkinter
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

---

## 📂 Project Structure

```text
Average-Fuel-Consumption/
│
├── dataset/
│   ├── fuel_dataset.csv
│   └── test_data.csv
│
├── fuel_prediction.py
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/average-fuel-consumption.git
```

### 2. Navigate to the Project Folder

```bash
cd average-fuel-consumption
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow keras
```

---

## ▶️ How to Run

Run the application:

```bash
python fuel_prediction.py
```

---

## 📊 Workflow

1. Upload Heavy Vehicle Fuel Dataset
2. Generate Training and Testing Data
3. Train ANN Model
4. Evaluate Accuracy
5. Upload Test Dataset
6. Predict Average Fuel Consumption
7. Visualize Predictions using Graph

---

## 🧠 ANN Architecture

Input Layer:
- 7 Input Features

Hidden Layers:
- Dense Layer (200 neurons, ReLU)
- Dense Layer (200 neurons, ReLU)

Output Layer:
- Dense Layer (19 neurons, Softmax)

Optimizer:
- Adam

Loss Function:
- Categorical Crossentropy

---

## 📈 Output

The application displays:

- Dataset size
- Training and testing data size
- ANN accuracy score
- Predicted fuel consumption values
- Fuel consumption graph

---

## 📷 Screenshots

### Main Interface

(Add screenshot here)

### Prediction Output

(Add screenshot here)

### Fuel Consumption Graph

(Add screenshot here)

---

## 🔮 Future Enhancements

- Replace ANN with advanced models
- Add Random Forest and XGBoost comparison
- Improve prediction accuracy
- Deploy as a web application using Flask or Django
- Add real-time vehicle data integration

---

## 👨‍💻 Author

**Kasulu Jalasutram**

GitHub: https://github.com/YOUR_USERNAME

LinkedIn: Add Your LinkedIn Profile

---

## 📄 License

This project is intended for educational and research purposes.
