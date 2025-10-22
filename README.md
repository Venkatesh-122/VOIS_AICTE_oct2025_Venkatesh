```markdown
# 🏡 Airbnb Data Analysis Project

## 📋 Project Overview
This project explores and analyzes Airbnb data to uncover insights about pricing trends, availability, host performance, and neighborhood popularity.  
The dataset contains details about Airbnb listings such as property type, host information, location, pricing, reviews, and availability.

The goal is to **understand key factors affecting Airbnb listings** and provide visual, data-driven insights for better decision-making.

---

## 🎯 Problem Statement
Airbnb provides various types of listings across different neighborhoods with varying prices, availability, and review patterns.  
However, these factors are not always obvious to users or hosts.  
The objective of this analysis is to **identify trends and relationships** within the dataset that help:
- Hosts optimize pricing and availability.  
- Travelers choose better listings.  
- Analysts understand the Airbnb market behavior.

---

## 💻 Technologies Used
| Tool / Library | Purpose |
|----------------|----------|
| **Python** | Programming and analysis |
| **Pandas** | Data cleaning and preprocessing |
| **Seaborn & Matplotlib** | Data visualization |
| **Plotly** *(optional)* | Interactive dashboards |
| **Google Colab / Jupyter Notebook** | Code execution and documentation |
| **Excel** | Initial dataset exploration |

---

## 🧹 Data Cleaning Summary
Before visualization, several cleaning steps were performed:
- Removed invalid or missing values (`NaN`, empty strings).  
- Fixed incorrect `last_review` entries (e.g., 1900 placeholder dates).  
- Replaced negative values in columns like *minimum nights* and *availability 365*.  
- Handled null columns (`host name`, `price`, `service fee`, etc.) appropriately.  
- Ensured correct data types for numeric and datetime columns.  

After cleaning, the dataset was ready for exploratory data analysis (EDA).

---

## 📊 Visualization & Analysis

| No. | Analysis Question | Visualization Type | Insights |
|-----|-------------------|--------------------|-----------|
| **1** | What are the different types of rooms available? | Countplot | Entire home/apartment listings dominate. |
| **2** | Which neighborhood groups have the most listings? | Countplot | Manhattan and Brooklyn have the highest density. |
| **3** | What is the average price across neighborhoods? | Bar Plot | Central areas show significantly higher prices. |
| **4** | Is there any relation between construction year and price? | Scatter Plot | Newer properties often priced higher. |
| **5** | Who are the top 10 hosts with most listings? | Bar Plot | Few hosts manage a large number of listings. |
| **6** | How do review ratings vary by room type? | Box Plot | Entire apartments tend to have consistent reviews. |
| **7** | What’s the relationship between price and service fee? | Scatter Plot | Service fees increase slightly with price. |
| **8** | How is property availability distributed throughout the year? | Histogram | Majority are available for <150 days/year. |
| **9** | How do reviews vary by neighborhood group? | Bar Plot | Central boroughs receive more frequent reviews. |
| **10** | What correlations exist among numerical features? | Heatmap | Strong link between price, availability, and reviews. |

All visuals are created using **Seaborn** and saved under the `plots/` folder for easy GitHub rendering.

---

## 👥 End Users
- **Airbnb Hosts** → Optimize pricing and listing strategy.  
- **Travelers** → Choose better areas and stay types.  
- **Business Analysts** → Understand market trends.  
- **Researchers / Students** → Learn data analysis workflows.  
- **Local Tourism Boards** → Assess housing and tourism impact.

---

## 📁 Project Structure

```

📦 Airbnb-Data-Analysis
┣ 📂 plots/                     # Saved Seaborn visualizations (PNG)
┣ 📜 Airbnb_Analysis.ipynb       # Main Jupyter notebook
┣ 📊 Airbnb_Open_Data.xlsx       # Dataset
┣ 🧾 README.md                   # Project description
┗ 📜 Airbnb_Interactive.html     # Optional Plotly dashboard

````

---

## 🚀 How to Run the Project

1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/Airbnb-Data-Analysis.git
   cd Airbnb-Data-Analysis
````

2. **Install dependencies**

   ```bash
   pip install pandas seaborn matplotlib plotly
   ```

3. **Run the notebook**

   ```bash
   jupyter notebook Airbnb_Analysis.ipynb
   ```

4. **View visualizations**

   * All Seaborn charts will be saved in `/plots/`
   * Optional Plotly dashboard: `Airbnb_Interactive.html`

---

## 🏁 Conclusion

This project provides a visual understanding of Airbnb listing behavior:

* Central neighborhoods are more popular and expensive.
* Most listings are *entire homes/apartments*.
* Pricing and availability vary significantly by area.
* Reviews and host activity reveal platform engagement patterns.

These insights can help **hosts, travelers, and analysts** make data-driven decisions.

---

## 🧑‍💻 Author

**M. Venkatesh**
Data Analyst | Python Developer | Machine Learning Enthusiast
📧 venkateshvenkateah789@gmail.com

---
