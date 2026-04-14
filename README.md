# 📊 Social Media Data Analysis

## 🔍 Overview
In this project, I used **Python** to extract insights from raw social media text data.

The main objective was to understand how to clean messy, unstructured data and convert it into a structured format for meaningful analysis.

---

## 🛠️ Approach

- Built a data processing pipeline on a small dataset  
- Cleaned raw text data into a structured format  
- Converted string-based numerical values into integers  
- Performed basic analysis to extract insights  

---

## 📂 Dataset

The dataset was a **text file** containing social media information such as:
- Username  
- Name  
- Number of posts  
- Followers  
- Following  
- Account type/category  
- Bio  

### ⚠️ Challenges in Dataset
- Data was highly unstructured and messy  
- Some users had missing or incomplete information  
- Inconsistent formats (e.g., `"10k"`, `"2.5k"`)  
- Irregular spacing and formatting  

---

## 🔧 Data Cleaning Techniques

- Split raw text into chunks (each representing one user)  
- Used string manipulation (`split`, `replace`, `strip`) for extraction and cleaning  
- Converted values like `"10k"` → `10000`  
- Handled missing (`None`) values using conditional logic (`if-else`)  
- Removed invalid or incomplete data entries  
- Stored cleaned data into a **JSON file** using the `json.dump()` method for better readability and structure  

---

## 📈 Key Findings

- 📌 User with the maximum number of posts  
- 📌 User with the highest number of followers  
- 📌 User following the most accounts  
- 📌 Unique categories/types of accounts present  

---

## 🚧 Problems Faced

- Parsing each user's data as a chunk was complex  
- Converting string values into integers required careful handling  
- Managing `"k"` (thousands) format was challenging  
- Handling empty or `None` chunks required additional logic  

---

## 💡 Key Learnings

- Data cleaning is the most time-consuming and critical step in data analysis  
- Real-world data is rarely clean and requires preprocessing  
- String manipulation is a powerful skill when working with raw datasets  

---

## 🧰 Tools Used

- Python  
- Built-in string functions (`split`, `replace`, `strip`)  
- `json` module  

---

## 📌 Conclusion

This project highlights the importance of data preprocessing and demonstrates how raw, messy data can be transformed into meaningful insights using Python.

