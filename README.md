
# 💼 **HR Analytics Dashboard** 📊

![HR Analytics Dashboard](https://github.com/ShubhamMvernekar/HR-Analytics-Dashboard/blob/main/HR%20Analytics_dashboard.png)  
**A Comprehensive HR Analytics Dashboard Powered by Power BI** 🎯

Welcome to the **HR Analytics Dashboard** project! This dashboard is designed to visualize key HR metrics and employee data. With the help of **Power BI** for advanced data visualization and **Power Query** for data cleaning, this project aims to provide valuable insights to HR professionals for making data-driven decisions regarding recruitment, retention, performance, and more.

## 🚀 **Project Overview**

The **HR Analytics Dashboard** provides an intuitive and interactive platform for HR managers to analyze various aspects of employee data, such as:
- Employee demographics
- Recruitment trends
- Performance evaluations
- Attrition rates
- Salary distribution

By leveraging **Power BI** and **Power Query**, the dashboard allows for easy exploration of employee data, helping HR teams monitor workforce health and optimize hiring and retention strategies.

## 🛠️ **Tools & Technologies**

This project uses the following technologies:
- **Power BI**: For creating interactive and visually appealing dashboards.
- **Power Query**: For cleaning, transforming, and shaping the data before analysis.
- **Excel**: As a data source, along with Power BI integration for seamless analysis.
- **DAX**: For creating calculated measures and columns in Power BI.

## 🔧 **Installation & Setup**

To work with this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ShubhamMvernekar/HR-Analytics-Dashboard.git
   cd HR-Analytics-Dashboard
   ```

2. **Power BI Desktop**:
   - Install **Power BI Desktop** if you don't have it already: [Download Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/).
   - Open the **HR Analytics Dashboard (.pbix)** file in **Power BI Desktop**.
   - All the necessary data sources and visualizations are already set up in the Power BI file.

3. **Power Query for Data Cleaning**:
   - Power Query is used to clean and transform the raw data before visualization. You can find the transformations applied in the **Power Query Editor** within Power BI.
   - To view and modify the data cleaning steps, go to **Home → Transform Data**.

4. **Start Exploring**:
   - Once you've opened the **.pbix** file in Power BI, the interactive dashboard will load, allowing you to explore different visualizations and gain insights into employee data.

## 📂 **Project Structure**

Here's how the project is organized:
- `assets/`: Contains images, logos, and other assets.
- `data/`: Contains raw data files (if applicable).
- `HR_Analytics_Dashboard.pbix`: Power BI file containing the dashboard and visualizations.
- `README.md`: This file, explaining the project and guiding you through the steps.

## 📊 **Dashboard Features**

### 1. **Employee Demographics** 👥
The dashboard includes visualizations of employee demographics such as age, gender, and tenure. This data helps HR managers better understand the composition of the workforce.

#### Example Visualization: Age Distribution
![Age Distribution](https://via.placeholder.com/800x400?text=Age+Distribution)  
*Bar chart showing the age distribution of employees.*

### 2. **Recruitment Trends** 📅
Track recruitment trends over time to assess hiring strategies and workforce growth. The trend data allows HR to analyze the success of recruitment campaigns.

#### Example Visualization: Recruitment Over Time
![Recruitment Trends](https://via.placeholder.com/800x400?text=Recruitment+Trends)  
*Line chart showing the number of recruits over the years.*

### 3. **Performance Evaluation** 🏆
Visualize employee performance evaluations across different departments or teams. This helps in identifying top performers and areas needing improvement.

#### Example Visualization: Performance Distribution
![Performance Evaluation](https://via.placeholder.com/800x400?text=Performance+Evaluation)  
*Bar chart or heatmap showing performance ratings across departments.*

### 4. **Attrition Rates** ⚠️
The dashboard visualizes employee attrition rates, helping HR teams understand turnover patterns and develop retention strategies.

#### Example Visualization: Attrition Rate by Department
![Attrition Rate](https://via.placeholder.com/800x400?text=Attrition+Rate)  
*Pie chart showing attrition rates by department.*

### 5. **Salary Distribution** 💸
Examine salary distribution across various departments and job roles. This helps HR in identifying pay gaps and ensuring competitive compensation strategies.

#### Example Visualization: Salary Distribution
![Salary Distribution](https://via.placeholder.com/800x400?text=Salary+Distribution)  
*Histogram showing salary distribution across departments.*

## 🔄 **Data Cleaning with Power Query**

The raw employee data undergoes significant transformations using **Power Query** before visualization in Power BI. This ensures that the data is in the correct format and that any inconsistencies are resolved.

### **Key Power Query Transformations**:
- **Removing duplicates**: Ensuring no duplicate records are present in the dataset.
- **Handling missing values**: Filling or removing missing values to ensure data integrity.
- **Creating calculated columns**: Such as tenure or salary bands, for more detailed analysis.
- **Merging data sources**: Combining multiple data sources (e.g., employee records, performance ratings, etc.) into a unified dataset for analysis.

You can view and modify these transformations directly in **Power Query Editor** by clicking on **Home → Transform Data** in Power BI.

## 💡 **Sample DAX Calculations**

Power BI's DAX (Data Analysis Expressions) language is used for creating calculated measures and columns. Here are some examples:

### Example: Calculating Attrition Rate
```DAX
Attrition Rate = 
    DIVIDE(
        COUNTROWS(FILTER(EmployeeData, EmployeeData[Status] = "Left")),
        COUNTROWS(EmployeeData)
    )
```

### Example: Calculating Average Salary
```DAX
Average Salary = 
    AVERAGE(EmployeeData[Salary])
```

## 🤝 **Contributing**

Contributions to the **HR Analytics Dashboard** project are welcome! Whether you have suggestions for new features, want to improve the visualizations, or have spotted a bug, feel free to fork the repository and submit a pull request.

If you encounter any issues, please open an issue, and I'll get back to you as soon as possible.


