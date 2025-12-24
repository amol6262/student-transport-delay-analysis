# Student Transport Delay Analysis 🚍🚆  
*A Professional Exploratory Data Analysis (EDA) Project*

---

## 📌  Project Overview

Course: Minor 1 Project

Difficulty: Medium

Student: Amol Tiwari (ERP: 6605417)

Student punctuality is strongly influenced by transportation reliability. Delays caused by traffic congestion, public transport inefficiencies, and environmental factors can negatively impact academic performance.  

This project performs a **comprehensive exploratory data analysis** on student transport delay data to uncover patterns, measure variability, and compare transport modes using statistical methods and visualizations.

The project is designed to be **simple, reproducible, and industry‑standard**, making it suitable for academic evaluation and technical training.

---

## 🎯 Objectives

- Analyze transport delay patterns among students  
- Compare delays between **Bus** and **Train** transport  
- Compute statistical measures such as **Mean** and **Standard Deviation**  
- Visualize insights using multiple graphs  
- Work with a **large, realistic dataset**  
- Follow clean project structure and documentation practices  

---

## 📁 Project Structure

```
student-transport-delay-analysis/
│
├── data/
│   └── student_transport_delay_extended.csv
│
├── src/
│   └── analysis.py
│
├── docs/
│   └── code_understanding_report.pdf
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🛠 Technologies Used

- **Python** – Core programming language  
- **NumPy** – Numerical operations  
- **Pandas** – Data manipulation and analysis  
- **Matplotlib** – Data visualization  

---

## 🗂 Dataset Description

The dataset simulates a **real-world college transport database** with **500+ records** and multiple attributes.

### Columns

| Column Name | Description |
|------------|-------------|
| Student_ID | Unique identifier for each student |
| Transport | Mode of transport (Bus / Train) |
| Delay_Minutes | Delay experienced in minutes |
| Distance_km | Distance from home to college |
| Departure_Time | Time student left home |
| Weather | Weather condition (Clear/Rainy/Foggy) |
| Day | Day of the week |

The dataset is stored in the `data/` directory.

---

## 📊 Methodology

1. Load the dataset from CSV  
2. Normalize and clean column names  
3. Group data by transport type  
4. Compute:
   - Mean delay
   - Standard deviation  
5. Visualize results using:
   - Bar chart
   - Histogram
   - Pie chart
   - Box plot  

---

## 📈 Output & Visualizations

Running the analysis generates:

- Average delay for each transport mode  
- Standard deviation indicating delay variability  
- Bar graph comparing average delays  
- Histogram showing delay distribution  
- Pie chart showing transport usage  
- Box plot highlighting spread and outliers  

These visualizations provide both **quantitative and intuitive insights**.

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/student-transport-delay-analysis.git
   ```

2. Navigate to the project directory:
   ```bash
   cd student-transport-delay-analysis
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the analysis:
   ```bash
   python src/analysis.py
   ```

---

## 📌 Real‑World Relevance

This project demonstrates how data analysis can support:
- Transport planning in educational institutions  
- Identification of unreliable transport modes  
- Data‑driven decision making  

The same methodology can be extended to other real‑world domains.

---


**Amol Tiwari**  
Technical Training Project  

---

