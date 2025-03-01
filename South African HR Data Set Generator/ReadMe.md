# 📊 South African HR Dataset Generator

This repository contains a Python script that generates a synthetic dataset representing workforce trends in South Africa. The dataset includes details about employees across various departments, provinces, cities, job titles, education levels, salaries, and performance ratings. The script can be used for HR analytics, trend analysis, and workforce insights.

## 📌 Contents

### Dataset Generation
- **Employee Details**: Generates unique employee IDs, names, gender, location (province and city), hire dates, departments, job titles, education levels, salaries, and performance ratings.
- **Departments & Job Titles**: Covers a range of South African industries, including HR, IT, Sales, Marketing, Finance, Operations, and Customer Service.
- **Geographical Distribution**: Randomly assigns employees to provinces and cities across South Africa.
- **Salary Generation**: Custom salary ranges based on job titles and departments.
- **Performance Ratings**: Randomly assigns performance ratings to each employee.

### Data Cleaning & Preparation
- Data is generated using the **Faker** library with realistic South African demographic information.
- Salary ranges and education levels are aligned with common South African employment standards.

### Geospatial Information
- **Provinces & Cities**: Employees are distributed across South Africa's provinces and cities.
- **Randomized Location Assignment**: Proportional probabilities are used to distribute employees across different regions.

## 🛠️ Tools & Technologies
- **Python** (pandas, numpy, faker) – Data generation and transformation
- **Libraries**: `pandas`, `numpy`, `faker`
- **Data Source**: Generated dataset saved as `SouthAfrica_HumanResources.csv`
- **Geographical Distribution**: Provinces and cities within South Africa.

### Example Data Columns
- `employee_id`: Unique identifier for each employee.
- `first_name`, `last_name`: Employee's full name.
- `gender`: Employee's gender (Male/Female).
- `province`: Employee's province.
- `city`: Employee's city.
- `hiredate`: Employee's hire date.
- `department`: Employee's department.
- `job_title`: Employee's job title.
- `education_level`: Employee's highest level of education.
- `salary`: Employee's annual salary in ZAR.
- `performance_rating`: Employee's performance rating.

## 🤝 Contributions
Feel free to explore, fork, and contribute! If you have suggestions or improvements, open an issue or submit a pull request.

## 📄 License
This project is licensed under the MIT License – see the LICENSE file for details.

## 🚀 Empowering HR teams with data-driven insights for workforce analysis! 🚀
