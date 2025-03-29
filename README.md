# Heart Disease Prediction

## 📌 Overview
This project is a **Heart Disease Prediction System** using **Machine Learning** and a graphical user interface (GUI) built with **Tkinter**. The system takes patient data as input and predicts whether they have heart disease or not.

## 🚀 Features
- User-friendly GUI with **Tkinter**
- Uses a **pre-trained Machine Learning model**
- Supports both **numerical** and **categorical** inputs with dropdown menus
- Displays **probability-based predictions** (if the model supports it)
- Alerts the user in case of missing or invalid inputs

## 🛠️ Tech Stack
- **Python**
- **Tkinter** (for GUI)
- **Scikit-Learn** (for ML model training and prediction)
- **NumPy** (for data processing)
- **Pickle** (for model serialization)

## 📂 Project Structure
```
/heart-disease-prediction
│── heart_model.pkl         # Trained ML model
│── main.py                 # Main Python script (GUI & Prediction Logic)
│── README.md               # Project documentation
│── requirements.txt        # Required dependencies
```

## 📥 Installation & Setup
### 1️⃣ Clone the repository
```sh
git clone https://github.com/yourusername/heart-disease-prediction.git
cd heart-disease-prediction
```

### 2️⃣ Install dependencies
```sh
pip install -r requirements.txt
```

### 3️⃣ Run the application
```sh
python main.py
```

## 🎯 Usage
1. Enter **patient details** (age, cholesterol, chest pain type, etc.).
2. Click the **Predict** button.
3. View the **diagnosis result** and probability.

## 📝 Data Fields
| Feature          | Description |
|----------------|-------------|
| Age            | Age of the patient (years) |
| Sex           | Male (M) / Female (F) |
| ChestPainType | TA, ATA, NAP, ASY |
| RestingBP      | Resting blood pressure (mmHg) |
| Cholesterol    | Serum cholesterol (mg/dl) |
| FastingBS      | 1 (FastingBS > 120) / 0 (otherwise) |
| RestingECG     | Normal, ST, LVH |
| MaxHR         | Maximum heart rate achieved |
| ExerciseAngina | Y (Yes) / N (No) |
| Oldpeak       | Depression ST |
| ST_Slope      | Up, Flat, Down |

## 🔗 Future Improvements
- ✅ Improve model accuracy with additional datasets.
- ✅ Add real-time **data visualization**.
- ✅ Deploy as a **web app** for broader access.

## 📌 Contributing
Contributions are welcome! Feel free to **fork** the repository and submit a **pull request**.

## 📜 License
This project is licensed under the **MIT License**.

---
🚀 **Developed by [HosnyFadda]**


