# 🚀📊 End-to-End Data Analytics Project (Python + SQL) 


## 🚀 Project Overview
This project demonstrates an end-to-end data analytics workflow. Using Python for data preprocessing and SQL Server for data storage and analysis, the goal is to extract, clean, transform, and analyze sales data to uncover meaningful insights that drive business decisions.

## 📌 Key Features
- **Extract:** Fetched retail order data using the **Kaggle API**.
- **Transform:** Cleaned, processed, and optimized the dataset using **pandas**.
- **Load:** Stored the refined data into **SQL Server** for querying and analysis.

## 🛠️ Steps Involved

### 1. 📥 Data Extraction
- Utilize the **Kaggle API** to download the dataset.  
- Extract files from the downloaded ZIP archive for further processing.  

### 2. 🧹 Data Preprocessing
Using **Python (Pandas)** for data cleaning and transformation:
- **Read and clean the data:**  
  - Handle missing values.  
  - Rename columns to follow a consistent format (lowercase, replace spaces with underscores).  
- **Derive new columns:**  
  - `discount` = `list_price` - `sale_price`  
  - `profit` = `sale_price` - `cost_price`  
- **Date formatting:**  
  - Convert `order_date` from string/object to `datetime` format.  
- **Column reduction:**  
  - Drop unnecessary columns: `cost_price`, `list_price`, `discount_percent`.  

### 3. 💾 Loading Data into SQL Server
- Load the cleaned dataset into **SQL Server** using the **append** option initially.  
- Reload the data using the **replace** option after additional transformations.  

### 4. 📊 Data Analysis & Insights
Perform analysis to derive actionable insights:
1. **Top revenue-generating products:**  
   - Identify the top 10 products generating the highest revenue.  
2. **Regional performance:**  
   - Find the top 5 highest-selling products for each region.  
3. **Month-over-month sales growth:**  
   - Compare sales growth between 2022 and 2023.  
4. **Category-wise sales peaks:**  
   - Determine which month recorded the highest sales for each product category.  
5. **Profit growth trends:**  
   - Identify the sub-category with the highest profit growth in 2023 compared to 2022. 



## 🔧 Technologies Used
- **Python**: For data cleaning, preprocessing, and transformation (Pandas, NumPy).  
- **SQL Server**: For structured data storage and querying.  
- **Kaggle API**: For efficient dataset acquisition.  
- **Matplotlib/Seaborn (optional)**: For data visualization. 

## 📂 Archiecture

![alt text](image-1.png)

## 🔮 Future Improvements 
- **Automate the pipeline**: Use tools like Apache Airflow for scheduled and streamlined data workflows.  
- **Cloud storage**: Store the processed data in a Cloud Data Warehouse (e.g., Snowflake, Azure Synapse).  
- **Interactive dashboards**: Build business intelligence dashboards using Power BI or Tableau for real-time insights.  

---

## ✨ Key Takeaway 
This project represents a comprehensive approach to data analytics, encompassing **extraction**, **transformation**, and **analysis**. It highlights the practical application of Python and SQL to generate valuable business insights and lays the foundation for scalable and automated solutions.


## ⚡ How to Run the Project
1. **Clone the Repository**  
   ```sh
   git clone https://github.com/akhtarcloudx/ETL-Retail-Orders-Project.git
   cd Retail-Order-ETL
   ```
2. **Set Up Kaggle API**  
   - Download your Kaggle API key from [Kaggle](https://www.kaggle.com/).  
   - Place the `kaggle.json` file in  `C:\Users\YourUsername\.kaggle\` (Windows).  

## 📊 Insights & Learnings
- Gained hands-on experience with the **ETL process**.
- Strengthened my **Python (pandas) and SQL** skills.
- Learned how to use the **Kaggle API** for data extraction.
---

If you find this project useful, feel free to ⭐ the repo and contribute! Let's connect and grow together in the **Data Engineering** space. 🚀

### 💼🌐 Connect with Me
[LinkedIn](https://www.linkedin.com/in/shahrukh-s-95ab69164/) | [GitHub](https://github.com/ShahrukhSultan) |

