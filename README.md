# data_cleaner.py
​A powerful, automated Python data sanitization pipeline built with Pandas to clean, standardize, and format messy Excel and CSV datasets.
# Data Sanitizer Pro 🚀

An automated Python data cleaning and processing pipeline designed to transform messy, unformatted business leads and corporate datasets into pristine, ready-to-use CSV/Excel structures. Built using `pandas` and regex tracking.

## ✨ Core Features
* **Duplicate Elimination:** Instantly drops redundant or repeating rows automatically.
* **Header Standardization:** Cleans whitespace, forces lowercase, and formats headers to `snake_case`.
* **Contact Parsing:** Utilizes regular expressions (Regex) to strip formatting anomalies from phone numbers and lowercase email strings.
* **Missing Value Imputation:** Smart handling of missing data points by replacing blank text strings with logical standard defaults.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Primary Library:** Pandas
* **Pattern Matching:** Regex (`re`)

## 🚀 How It Works
1. Feed a messy `.csv` or `.xlsx` file into the configuration pipeline.
2. The script runs automated cleaning layers sequentially.
3. A clean, optimized dataset is exported instantly.
