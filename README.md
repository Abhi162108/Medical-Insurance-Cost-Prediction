# 🏥 Medical Insurance Cost Prediction  

This project predicts **medical insurance costs** based on factors like **age, gender, BMI, number of children, smoking habits, and region**.  
It uses **machine learning models** to analyze health and lifestyle data and estimate insurance charges.  

---

## 📊 Dataset  

The dataset contains information about individuals, including:  

| Feature   | Description |
|-----------|-------------|
| **age** | Age of the individual |
| **sex** | Gender (male/female) |
| **bmi** | Body Mass Index (measure of body fat) |
| **children** | Number of children/dependents covered by insurance |
| **smoker** | Whether the person is a smoker (yes/no) |
| **region** | Residential area (northeast, northwest, southeast, southwest) |
| **charges** | Medical insurance cost (target variable) |

Example rows:  

| age | sex | bmi   | children | smoker | region    | charges    |
|-----|-----|-------|----------|--------|-----------|------------|
| 19  | female | 27.90 | 0        | yes    | southwest | 16884.92   |
| 18  | male   | 33.77 | 1        | no     | southeast | 1725.55    |
| 28  | male   | 33.00 | 3        | no     | southeast | 4449.46    |

---

## 🛠️ Tech Stack  

- **Python 3.x**
- **Pandas / NumPy** – Data manipulation  
- **Matplotlib / Seaborn** – Visualization  
- **Scikit-learn** – Machine Learning (Linear Regression, Random Forest, etc.)  
- **Jupyter Notebook** – Development & experimentation  

---

## 🚀 Workflow  

```mermaid
flowchart TD
    A[📂 Collect Dataset] --> B[🧹 Data Preprocessing]
    B --> C[📊 Exploratory Data Analysis]
    C --> D[⚙️ Feature Engineering]
    D --> E[🤖 Model Training]
    E --> F[📈 Model Evaluation]
    F --> G[💾 Save Best Model]
    G --> H[🌐 Deploy Model]
    H --> I[🩺 Predict Insurance Cost]
