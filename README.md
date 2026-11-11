# 📊 Customer Shopping Behavior Analysis

## 1. Overview

This project focuses on analyzing customer shopping behavior to understand purchasing patterns, customer preferences, and spending habits.

An end-to-end data analytics approach is used to transform raw data into meaningful business insights using Python, SQL, and Power BI.

The project covers data loading, exploratory data analysis (EDA), data cleaning, SQL-based analysis, interactive dashboard development, and business reporting.

**Project Objectives:**

- Understand customer purchasing patterns and preferences.
- Analyze spending behavior across different product categories.
- Examine the relationship between discounts, subscriptions, and purchases.
- Identify trends based on customer demographics and shopping frequency.
- Present actionable insights through an interactive dashboard.

## 2. Dataset

- **Dataset Name:** Customer Shopping Behavior Dataset
- **Source:** Publicly available customer shopping behavior dataset.
- **Format:** CSV (`shopping_behavior_updated.csv`)
- **Records:** 3,900 rows
- **Features:** 18 columns

**Description:**

The dataset contains customer demographics, purchase details, and shopping behavior information. It includes customer age, gender, product categories, purchase amounts, locations, payment methods, discounts, subscription status, shipping preferences, and purchase frequency.

The dataset is used to explore customer preferences, analyze purchasing trends, and understand shopping behavior.

### Key Dataset Attributes

- Customer ID
- Age and Gender
- Item Purchased
- Product Category
- Purchase Amount (USD)
- Location
- Size and Color
- Season
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Promo Code Used
- Previous Purchases
- Payment Method
- Frequency of Purchases

## 3. Tools & Technologies

| Tool             | Purpose                                 |
| ---------------- | --------------------------------------- |
| Python           | Data loading, exploration, and cleaning |
| Pandas           | Data manipulation and preprocessing     |
| NumPy            | Numerical operations                    |
| Matplotlib       | Data visualization                      |
| Seaborn          | Statistical visualization and EDA       |
| MySQL            | SQL queries and data analysis           |
| SQLAlchemy       | Database connectivity                   |
| Power BI         | Interactive dashboard development       |
| Gamma            | Report presentation and slide creation  |
| Jupyter Notebook | Python development and analysis         |

## 4. Project Workflow

### Step 1: Data Loading

- Imported the CSV dataset into Python using Pandas.
- Examined the dataset dimensions, structure, and column information.
- Checked data types and initial data quality.
- Identified missing values and potential inconsistencies.

### Step 2: Exploratory Data Analysis (EDA)

- Performed descriptive statistical analysis.
- Examined customer demographics and purchasing patterns.
- Analyzed product categories and purchase amounts.
- Explored relationships between customer attributes and shopping behavior.
- Used Matplotlib and Seaborn to visualize distributions and trends.

### Step 3: Data Cleaning & Preprocessing

- Identified and handled missing values.
- Checked for duplicate records.
- Standardized column names and data formats.
- Removed redundant information where appropriate.
- Created additional analytical features where required.
- Prepared the cleaned dataset for SQL analysis.

### Step 4: SQL Analysis

- Connected the cleaned dataset to a MySQL database.
- Loaded the processed data into the database.
- Executed SQL queries to answer business-related questions.
- Used filtering, sorting, aggregate functions, GROUP BY, and subqueries.
- Analyzed customer segments, product categories, purchase patterns, and spending behavior.
- Extracted meaningful insights from the query results.

### Step 5: Power BI Dashboard

- Imported the analyzed data into Power BI.
- Created KPI cards to display important business metrics.
- Developed charts and graphs to represent customer shopping trends.
- Used slicers and filters for interactive data exploration.
- Designed a dashboard to present findings in a clear and understandable format.

### Step 6: Report & Presentation

- Prepared a project report covering the analysis process and findings.
- Summarized important insights and business observations.
- Created a professional PowerPoint presentation using Gamma.
- Organized the project methodology, dashboard highlights, and conclusions into presentation slides.

## 5. Power BI Dashboard

The interactive Power BI dashboard provides an overview of customer purchasing patterns, product preferences, and shopping behavior.

### Dashboard Features

- Customer and purchase-related KPIs.
- Category-wise purchasing analysis.
- Customer demographics and segmentation.
- Purchase amount analysis.
- Subscription and discount analysis.
- Payment method and shipping preference analysis.
- Interactive filters and slicers.

### Dashboard Preview

**Power BI File:** `customer_shopping_behavior.pbix`

## 6. Results & Key Insights

The analysis provides insights into customer demographics, purchasing patterns, product preferences, and shopping behavior.

### Dataset Observations

- Analyzed 3,900 customer purchase records.
- Examined 18 customer and purchase-related attributes.
- Identified 37 missing values in the Review Rating column of the original dataset.
- Explored four major product categories: Clothing, Accessories, Footwear, and Outerwear.

### Business Insights

The analysis focuses on identifying:

- Product categories that attract more customer purchases.
- Differences in purchasing behavior across customer demographics.
- Customer spending patterns and purchase frequency.
- The relationship between discounts and purchasing behavior.
- Subscription trends and customer engagement.
- Preferred payment methods and shipping options.

The findings can help businesses better understand customers and make informed decisions regarding marketing, product offerings, and customer engagement.

## 7. Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── dataset/
│   └── shopping_behavior_updated.csv
│
├── notebooks/
│   └── customer_shopping_analysis.ipynb
│
├── sql/
│   └── customer_analysis.sql
│
├── dashboard/
│   ├── customer_shopping_behavior.pbix
│   └── dashboard_preview.png
│
├── reports/
│   └── project_report.pdf
│
├── presentation/
│   └── project_presentation.pptx
│
├── requirements.txt
│
└── README.md
```

## 8. How to Run

### Prerequisites

- Python 3.x
- Jupyter Notebook
- MySQL Server
- Power BI Desktop

### Installation & Setup

**1. Clone the repository**

```bash
git clone https://github.com/your-username/Customer-Shopping-Behavior-Analysis.git
```

**2. Navigate to the project directory**

```bash
cd Customer-Shopping-Behavior-Analysis
```

**3. Install the required Python libraries**

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy pymysql jupyter
```

**4. Launch Jupyter Notebook**

```bash
jupyter notebook
```

Open the notebook inside the `notebooks` folder and execute the cells to load, explore, and clean the dataset.

**5. Set up the MySQL database**

- Start your MySQL Server.
- Create a database for the project.
- Configure the database connection in the Python notebook.
- Load the cleaned dataset into the MySQL database.

**6. Execute SQL queries**

Open the SQL file inside the `sql` folder and execute the queries using MySQL Workbench or another compatible SQL client.

**7. Open the Power BI Dashboard**

Open the `.pbix` file using Power BI Desktop. Configure the data connection if required to explore the dashboard.

**8. View the Project Documentation**

Refer to the `reports` and `presentation` folders for the final project report and presentation.

## 9. Conclusion

This project demonstrates an end-to-end data analytics workflow using Python, SQL, and Power BI.

By combining data exploration, data cleaning, database analysis, and interactive visualization, the project transforms raw customer shopping data into meaningful business insights.

It highlights the importance of data-driven decision-making in understanding customer behavior, identifying purchasing trends, and supporting business strategies.

---

**Technologies:** Python | Pandas | NumPy | MySQL | SQL | Power BI | Gamma

**Project Category:** Data Analytics
