

# 🏠 House Price Data Cleaning Script 🧹

A simple and efficient Python script to clean the **House Price Prediction** dataset. It prepares your data by removing invalid and missing entries, making it ready for analysis or modeling.

---

## ✨ Features

* 📥 Load data from Excel (`.xlsx`)
* 🔍 Initial data inspection and summary statistics
* 🚫 Remove rows with zero or negative values in critical columns:

  * `LotArea`, `YearBuilt`, `YearRemodAdd`, `TotalBsmtSF`, `SalePrice`
* 🧽 Drop rows with missing values
* 🔢 Keep only numeric columns
* 💾 Save cleaned data to a new Excel file

---

## 🚀 Usage

1. Place your dataset here:

   ```
   c:\Ds\HousePricePrediction.xlsx
   ```

2. Run the cleaning script:

   ```bash
   python data_cleaning.py
   ```

3. Find the cleaned dataset here:

   ```
   Cleaned_HousePricePrediction.xlsx
   ```

---

## 📊 Output

* Cleaned Excel file with only valid records
* Console printout with the count of remaining records

---

## ⚙️ Requirements

* Python 3.x
* pandas
* openpyxl

Install dependencies:

```bash
pip install pandas openpyxl
```

---

## 📝 Notes

* Adjust `zero_check_columns` in the script if your dataset has different column names.
* Ideal for preprocessing before machine learning or statistical analysis.

