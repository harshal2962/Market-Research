# 🏠 Student Housing Market Research – Greater Lafayette

This project investigates the housing preferences of Purdue University students living in Greater Lafayette, Indiana. Using survey responses and unsupervised machine learning, we identified distinct student segments based on pricing sensitivity, amenity preferences, and lifestyle factors. The insights help real estate providers tailor offerings, leasing strategies, and marketing efforts.

---

## 📌 Project Objective

To assist campus-area housing providers in optimizing their property offerings by understanding the **most influential factors** that drive Purdue students’ housing decisions — including price, location, safety, lease flexibility, and amenity preferences.

---

## 🎯 Goals

- Segment students based on their housing preferences and financial willingness.
- Identify critical decision factors such as proximity to campus, safety, and lease terms.
- Offer actionable recommendations for real estate developers and university housing stakeholders.

---

## 🧪 Methodology

### Data Collection:
- **Tool:** Qualtrics (Survey)
- **Method:** Convenience sampling via WhatsApp groups and social media
- **Responses:** 67 Purdue students across academic levels and housing types

### Tools Used:
- **Python (Google Colab)** for data preprocessing and clustering
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

### Steps:
1. **Data Cleaning:** Imputation of missing values (median for numeric, mode for categorical)
2. **Feature Engineering:** One-hot encoding for categorical data
3. **Standardization:** Used `StandardScaler` to prepare data for clustering
4. **Clustering:** K-Means clustering with elbow method to determine optimal number of clusters
5. **Visualization:** Created bar charts, heatmaps, and segment-based plots to explore behavior

---

## 🔍 Key Findings

### 🧩 Identified Segments:
1. **On-Campus Convenience Seekers** – Proximity and safety-focused, rent-insensitive
2. **Premium Off-Campus Renters** – Amenity-rich, lifestyle-focused, rent-flexible
3. **Budget-Conscious Renters** – Highly price-sensitive, prioritize cost over extras

### 🧠 Student Priorities:
- **Top Factors:** Affordability, Proximity to Campus, Safety
- **Top Amenities:** In-unit laundry, 24/7 maintenance, study areas
- **Rent Willingness:** 71% of students prefer rent between $500–$1000
- **Flexible Leases:** Highly valued by international students and seniors

---

## 📈 Impact

- Developed **cluster-based recommendations** for property owners:
  - Tiered pricing models
  - Segment-specific amenity planning
  - Flexible lease offerings
  - Safety-driven design
- Provided data-driven insights to enhance **occupancy rates** and **marketing alignment**

---

## 🛠 Technologies Used

- Python · Scikit-learn · Seaborn · Matplotlib · Qualtrics · Google Colab

---

## 👥 Team

- Harshal Amin and Team 06 (Purdue University)
- Course: Marketing Research, Daniels School of Business

---

## 📌 Files Included

- `housing_survey_data.csv` – Cleaned dataset
- `colab_analysis.ipynb` – Data cleaning, clustering, and EDA
- `presentation.pdf` – Summary insights and recommendations
- `survey_link.txt` – Original Qualtrics form (for reference)

---

## 📎 License

This project is for academic and educational use.
