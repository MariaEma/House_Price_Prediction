# 🏠 House Price Prediction using Linear Regression

This is a simple Python project that uses **linear regression** to predict house prices based on the area (in square feet). The project is implemented using `pandas` and `scikit-learn`.

---

## 📌 Features

- Takes area as user input
- Predicts house price using a trained linear regression model
- Clean and simple code
- Easily extendable with more features

---

## 🧠 Algorithms Used

- **Linear Regression** from `sklearn.linear_model`

---

## 📊 Sample Dataset

| Area (sq ft) | Price (Tk) |
|--------------|------------|
| 1000         | 30000      |
| 1500         | 45000      |
| 2000         | 60000      |
| 2500         | 75000      |
| 3000         | 90000      |

---

## 📦 Requirements

- Python 3.x
- pandas
- scikit-learn

You can install the dependencies using pip:

```bash
pip install pandas scikit-learn
🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
Run the script:

bash
Copy
Edit
python predict_price.py
Enter the area when prompted:

yaml
Copy
Edit
Enter Area:
2000
Predicted Price: Tk 60,000.00
🛠️ File Structure
bash
Copy
Edit
.
├── predict_price.py   # Main Python script
└── README.md          # This documentation
📈 Future Improvements
Add more input features (e.g., number of rooms, location)

Visualize data and regression line using matplotlib

Build a web app interface with Flask or Streamlit
