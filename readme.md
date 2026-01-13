

# 🔫 **Weapon Data Analysis using Web Scraping & Data Science**

## 📌 Project Overview

This project focuses on collecting, cleaning, and analyzing **weapon data** from an online store using **Python-based web scraping** and **data analysis techniques**.
The goal is to transform unstructured weapon information into a structured dataset and generate insights related to **price, weapon type, customer ratings, brands, and power sources**.  

The dataset was scraped from:
🔗 [https://airsoftstation.com/](https://airsoftstation.com/) 

---

## 🧠 Problem Statement

Weapon data available online is:

* Highly **unstructured**
* Uses **inconsistent units** (kg/lb, cm/inch)
* Contains **missing or duplicate values**

There is no centralized dataset to analyze:

* Price patterns
* Weapon categories
* Performance vs cost
* Brand popularity

This project solves that problem by creating a **clean, structured, and analyzable weapon database**. 

---

## 🎯 Objectives

* Scrape weapon data from an online store
* Clean and standardize inconsistent values
* Store the data in a structured format (CSV / SQL)
* Perform statistical and visual analysis
* Extract insights on pricing, ratings, and weapon types



---

## ⚙️ Technologies Used

* **Python**
* **Requests** – For fetching web pages
* **BeautifulSoup** – For extracting data
* **Pandas** – Data cleaning and analysis
* **Matplotlib & Seaborn** – Visualization
* **SQL / CSV** – Data storage

---

## 🛠️ Web Scraping Workflow

The scraping process followed four main steps:

1. **Find Website & Collect Data**

   * Selected airsoftstation.com
   * Fetched page content using `requests`

2. **Read the Page**

   * Extracted:

     * Weapon Name
     * Price
     * Type
     * Weight
     * Length
     * Size

3. **Clean the Data**

   * Removed symbols (₹, $, cm, kg)
   * Converted units
   * Handled missing and duplicate values

4. **Save & Check**

   * Stored data in CSV/SQL
   * Verified data completeness



---

## 📊 Dataset Features

After cleaning, the dataset contains the following key columns:

* Weapon Name
* Type (Pistol, Rifle, SMG, Shotgun, Sniper)
* Cost
* Weight
* Length
* Range
* Magazine Capacity
* Caliber Diameter
* Customer Rating
* Brand
* Power Source
* Availability



---

## 📈 Key Analyses Performed

### 1️⃣ Weapon Cost Distribution

A histogram shows prices ranging from **₹25,000 to ₹2,00,000**, with slightly more weapons in the **₹1,50,000–₹2,00,000** range. 

### 2️⃣ Weapon Type Frequency

Most common weapons:

* **Pistols**
* **SMGs**
* **Shotguns**
  Least common:
* **Snipers** 

### 3️⃣ Customer Ratings

Most weapons are rated toward the **higher end (3–5 stars)**, showing generally good customer satisfaction. 

### 4️⃣ Average Rating by Weapon Type

| Weapon Type | Avg Rating |
| ----------- | ---------- |
| Shotgun     | **3.17**   |
| Sniper      | 3.01       |
| Rifle       | ~2.8       |
| Pistol      | ~2.8       |
| SMG         | ~2.8       |

Shotguns are the **best-rated** weapons. 

### 5️⃣ Brand Market Share

Top brands:

* **Tokyo Marui – 26.1%**
* **CYMA – 25.8%**
* **Lancer Tactical – 25.8%**
* **G&G – 22.4%** 

### 6️⃣ Power Source Distribution

| Power Source | Share     |
| ------------ | --------- |
| Gas          | **29.8%** |
| Spring       | 26.7%     |
| Electric     | 25.5%     |
| CO2          | 18.1%     |

Gas-powered weapons dominate the market. 

### 7️⃣ Cost vs Rating

Some high-priced weapons have **low ratings**, while some moderately priced ones have **higher satisfaction**, indicating that **higher price ≠ better quality**. 

### 8️⃣ Correlation Analysis

* Cost vs FPS → **0.12** (weak positive)
* Cost vs Length → **0.11**
* Magazine Capacity vs Caliber → **-0.09**

Most features have **weak correlations**, meaning they are mostly independent. 

---

## 🧩 Conclusion

This project successfully:

* Converted unstructured web data into a clean dataset
* Revealed patterns in **weapon types, pricing, ratings, brands, and power sources**
* Helped identify which weapons offer **better value for money**

These insights can help:

* Manufacturers
* Defense researchers
* Market analysts
* Retailers



---

## 🚀 Future Enhancements

* Scrape data from **multiple websites**
* Include **reviews and sentiment analysis**
* Build **interactive dashboards (Power BI / Tableau)**
* Use **Selenium or APIs** for automated data extraction



---

## 👩‍💻 Author

**Vaibhavi Tayade**
Bachelor of Computer Applications – HVM, Amravati

🔗 LinkedIn: [https://www.linkedin.com/in/vaibhavi-tayade-70a444303/](https://www.linkedin.com/in/vaibhavi-tayade-70a444303/)
🔗 GitHub: [https://github.com/vaibhavitayade](https://github.com/vaibhavitayade)
