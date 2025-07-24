# Mobile Phone Pricing Prediction

## 📝 Project Overview
This project aims to build a machine learning model that predicts the price category of mobile phones based on various features such as battery power, RAM, camera specs, and connectivity.

The goal is to classify mobile phones into one of the four price ranges (0 to 3), helping manufacturers or e-commerce platforms understand product segmentation.

## 📊 Dataset Description
Key features used in this project include:
- **battery_power**
- **ram**
- **mobile_wt**
- **int_memory**
- **px_height / px_width**
- **primary_camera / front_camera**
- **4G, 3G, Bluetooth, Wi-Fi, Dual SIM support**
- **price_range** (Target: 0 = Low, 3 = High)

The dataset is balanced and contains no missing values, making it ideal for classification tasks.

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn (RandomForest, Logistic Regression, etc.)
- Seaborn, Matplotlib

## 🚀 How to Run
1. Clone the repository or download the notebook.
2. Open `Mobile_phone_pricing.ipynb` in Jupyter or Google Colab.
3. Run all cells to:
   - Explore the data
   - Train classification models
   - Evaluate model accuracy and performance

## 📈 Results
The model classifies mobile phones into correct price ranges with high accuracy using machine learning algorithms such as Decision Trees and Random Forests.

## 📁 File Structure
- `Mobile_phone_pricing.ipynb` – Main notebook
- `mobile-phone-pricing.csv` – Dataset used

## 📜 License
This project is created for academic and learning purposes only.
