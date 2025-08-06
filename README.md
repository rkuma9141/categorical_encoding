# Categorical Encoding in Machine Learning

This project demonstrates various categorical encoding techniques used to convert categorical (textual) data into numerical format so that machine learning models can process them effectively.

## 📌 What is Categorical Encoding?

Categorical encoding is the process of converting non-numerical labels (like "Red", "Male", "India") into numerical formats (like 0, 1, 2) using various encoding techniques.

## 🧠 Why Encoding is Important?

Machine learning algorithms work with numerical data. If the dataset contains categorical values, they must be encoded before model training.

---

## 🧰 Techniques Used

1. **Label Encoding**  
   Converts each label into a unique number.
   
2. **One-Hot Encoding**  
   Creates binary columns for each category.
   
3. **Ordinal Encoding**  
   Assigns ordered numeric values to categories.
   
4. **Binary Encoding**  
   Converts categories into binary numbers (good for high-cardinality).
   
5. **Target Encoding**  
   Replaces categories with the mean of the target variable for each category.

---

## 📂 Files in This Repository

- `label_encoding.py` – Code for Label Encoding
- `one_hot_encoding.py` – Code for One-Hot Encoding
- `ordinal_encoding.py` – Code for Ordinal Encoding
- `binary_encoding.py` – Code for Binary Encoding
- `target_encoding.py` – Code for Target Encoding (with target variable)
- `sample_dataset.csv` – Example dataset with categorical features
- `README.md` – Project overview and instructions

---

## 🧪 Example

### Sample Dataset:

| Name  | Gender | Color |
|-------|--------|--------|
| Ravi  | Male   | Red    |
| Sita  | Female | Blue   |

### One-Hot Encoded Output:

| Name  | Gender_Female | Gender_Male | Color_Red | Color_Blue |
|-------|---------------|-------------|-----------|------------|
| Ravi  | 0             | 1           | 1         | 0          |
| Sita  | 1             | 0           | 0         | 1          |

---

## ✅ How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/categorical-encoding.git
   cd categorical-encoding
