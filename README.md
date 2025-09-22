# Titanic Data Preprocessing – Task 1  

This project performs **data cleaning, preprocessing, and visualization** on the Titanic dataset using Python.  

## 📂 Files
- **data.py** → Python script that:
  - Loads Titanic dataset
  - Explores null values and data types
  - Handles missing values (median, mode, drop columns)
  - Encodes categorical features
  - Normalizes numerical columns
  - Visualizes outliers using boxplots
  - Removes extreme outliers (Fare)

- **Titanic-Dataset.csv** → Dataset used for preprocessing.

---

## ⚙️ Prerequisites
Make sure you have installed the following:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn

How to Run

Clone this repo:

git clone https://github.com/dinu-vishruth/task1.git
cd task1


Run the script:

python data.py


Boxplots will be generated for:

Age

Fare

🌱 Git Commands Used

Below are the exact steps followed to push this project to GitHub:

# Initialize Git repo
git init

# Link remote repository
git remote add origin https://github.com/dinu-vishruth/task1.git

# Add files
git add data.py Titanic-Dataset.csv

# Commit changes
git commit -m "task1"

# Rename branch to main (to match GitHub default)
git branch -M main

# Push to GitHub
git push -u origin main

📊 Output

Console:

First 5 rows of dataset

Shape (rows, columns)

Data types & null counts

Missing values (count & percentage)

Statistical summary

Plots:

Boxplot of Age

Boxplot of Fare
