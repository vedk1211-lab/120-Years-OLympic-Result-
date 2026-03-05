# 120-Years-OLympic-Result
---
This repository contains an **Exploratory Data Analysis (EDA) project** on the historical Olympic dataset.
The project analyzes **120 years of Olympic history** to uncover patterns in athlete participation, medal distribution, and country performance.

The analysis is performed using **Python, Pandas, and data visualization libraries**.

---

# 📌 Project Overview

The Olympic Games are one of the largest international sporting events.
This project explores historical Olympic data to answer questions such as:

* How has Olympic participation changed over time?
* Which countries have won the most medals?
* How has **female participation evolved** over the years?
* Which sports are most popular in the Olympics?
* What patterns exist in athlete age, height, and weight?

The dataset spans **from Athens 1896 to Rio 2016**.

---

# 📂 Dataset

The dataset used in this project is the **120 Years of Olympic History: Athletes and Results** dataset from Kaggle.

🔗 Dataset Link
[https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)

The dataset contains information about **271,000+ athlete records** and Olympic events.

---

# 📊 Dataset Files

### 1️⃣ athlete_events.csv

This file contains detailed information about athletes and Olympic events.

| Column | Description                     |
| ------ | ------------------------------- |
| ID     | Unique athlete ID               |
| Name   | Athlete name                    |
| Sex    | Gender (M/F)                    |
| Age    | Athlete age                     |
| Height | Height in cm                    |
| Weight | Weight in kg                    |
| Team   | Country team name               |
| NOC    | National Olympic Committee code |
| Games  | Year + season                   |
| Year   | Olympic year                    |
| Season | Summer / Winter                 |
| City   | Host city                       |
| Sport  | Sport category                  |
| Event  | Specific event                  |
| Medal  | Gold, Silver, Bronze or NA      |

---

### 2️⃣ noc_regions.csv

This file maps **NOC codes to country names**.

Example:

| NOC | Region        |
| --- | ------------- |
| USA | United States |
| IND | India         |
| FRA | France        |

---

# 🎯 Project Objectives

The main objectives of this project are:

* Analyze **Olympic participation trends**
* Study **gender representation in sports**
* Identify **top performing countries**
* Explore **medal distribution across sports**
* Understand **athlete demographic patterns**

---

# 🧠 Analysis Performed

### 1️⃣ Data Cleaning

* Handling missing values
* Removing duplicate records
* Merging athlete and country datasets

### 2️⃣ Exploratory Data Analysis (EDA)

The following analyses were performed:

* Olympic participation over the years
* Gender participation trends
* Country-wise medal counts
* Most popular sports
* Host city distribution
* Athlete physical characteristics

---

# 📈 Visualizations

The project includes multiple visualizations such as:

* 📊 Medal count bar charts
* 📈 Participation trends over time
* 🥧 Gender distribution pie charts
* 📊 Top countries by medal count
* 📈 Athlete age distribution
* 📊 Popular Olympic sports

These visualizations help better understand **historical Olympic patterns**.

---

# 🛠 Tech Stack

**Programming Language**

* Python

**Libraries Used**

* pandas
* numpy
* matplotlib
* seaborn
* plotly

**Development Environment**

* Google Colab / Jupyter Notebook

---

# 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/olympics-data-analysis.git
cd olympics-data-analysis
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn plotly
```

### Run the Notebook

```bash
jupyter notebook
```

Open the notebook and run all cells to reproduce the analysis.

---

# 📁 Project Structure

```
Olympics-Data-Analysis
│
├── data
│   ├── athlete_events.csv
│   └── noc_regions.csv
│
├── notebooks
│   └── olympics_analysis.ipynb
│
├── images
│   └── charts
│
├── README.md
└── requirements.txt
```

---

# 📊 Key Insights

Some key findings from the analysis include:

* Olympic participation has **increased significantly over time**.
* Female athlete participation has **grown rapidly in recent decades**.
* Countries like **USA, USSR, and Germany** dominate the medal tally.
* Certain sports such as **Athletics and Swimming** have the highest number of events.
* Athlete physical characteristics vary significantly across sports.

---

# Link
https://colab.research.google.com/drive/1qWnIRgEwD14neGRmJfH7zKkfZCJcfIfr?usp=sharing
