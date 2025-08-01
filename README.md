# 💻🔮 Laptop Price Predictor

A **machine learning-based web app** that predicts laptop prices based on user-selected configurations like CPU, RAM, storage, display features, brand, and more. Built using **Python**, **scikit-learn**, and saved using **Pickle**, this project helps estimate real-world laptop prices 💸.

---

## 🚀 Project Highlights

✨ Predicts price based on:
- 📦 Brand, Type, and Operating System
- 🔧 CPU & GPU
- 🎮 RAM, SSD, HDD
- 💡 Touchscreen & IPS Display
- 📏 Screen Size and Resolution
- ⚖️ Weight and Build

⚙️ Models Used:
- 🔹 Linear Regression
- 🔹 Ridge Regression
- 🔹 Lasso Regression
- ✅ ExtraTrees Regressor (Best Performance)

📈 Achieved R² score up to **0.83** and low MAE using real laptop listings from e-commerce sources.

---

## 🧠 Machine Learning Workflow

graph LR
A[Data Loading] --> B[Feature Engineering]
B --> C[EDA & Visualization]
C --> D[Train-Test Split]
D --> E[Train ML Models]
E --> F[Model Evaluation]
F --> G[Pickle Best Model]

---

Laptop_Price_Predictor/
│
├── data/                   # Raw dataset
├── app.py                  # Flask backend (optional)
├── model/pipe.pkl          # Trained ML pipeline
├── laptop-price-predictor.ipynb  # Main notebook
├── README.md               # Project readme
└── requirements.txt        # Required libraries

--

# 🌟 Future Improvements
🧠 Add XGBoost and LightGBM for boosted accuracy

🌐 Deploy using Flask/Streamlit

💾 Add cloud-based dataset storage

📊 Build interactive dashboard

---

# 📌 Screenshot 


https://github.com/user-attachments/assets/5fcfd960-d2ad-46f2-ae4b-4cb2382ed9a5

---

# Thank you for visit!
