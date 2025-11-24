# 🌿 Sustainable Travel SQL Analysis

**👩‍💻 Author:** Günel Xəlilli  
**📅 Date:** 2025-11-24  

This repository contains SQL queries and exploratory analysis performed on a **sustainable travel & carbon-emission dataset**.  
It includes tables for travelers, trips, transport modes, emission factors, and carbon-offset projects.  
The project demonstrates the use of **aggregation, JOINs, CO₂ calculations, date filtering, and analytical SQL techniques**.


🏗 Data Warehouse Explanation

This project uses a small data warehouse structure to organize the sustainable travel dataset.
Each table has a clear purpose and represents a different aspect of the data:

Travelers — stores personal information about each traveler (name, age, country, gender)

Trips — contains each trip taken, including destination, transport mode, distance, date, and duration

Emission Factors — stores CO₂ emission per kilometer for each transport mode

Offset Projects — details carbon-offset projects (e.g., reforestation, solar, wind)

Contributions — links travelers to offset projects, showing how much they contributed





## 📂 Repository Structure

- **📝 SQL.Questions.Solutions** — All SQL questions and solutions collected  
- **🖼 examples/** — Query output screenshots  
- **📜 LICENSE** — License file (MIT suggested)  




## 🧠 Topics Covered

### 🔹 Aggregate Functions
- `COUNT`, `SUM`, `AVG`, `MAX`  

### 🔹 CO₂ Emission Calculations
- Compute emissions per trip, per traveler, or per transport mode  

### 🔹 Multi-table JOINs
- Combine travelers, trips, emission factors, and contributions  

### 🔹 Conditional Logic
- `CASE WHEN` statements for conditional computations  

### 🔹 Date Filtering & Analysis
- Analyze trips or contributions over specific date ranges  

### 🔹 Window Functions
- `RANK()`, `ROW_NUMBER()`, `DENSE_RANK()` for ranking and analysis 





### Travelers Table
![Travelers Table](https://github.com/GunelXelilli/Eco-Travel-Data-Warehouse-PostgreSQL-Project-/blob/main/Travellersphoto.png)

### Trips Table
![Trips Table](https://github.com/GunelXelilli/Eco-Travel-Data-Warehouse-PostgreSQL-Project-/blob/main/Tripsphoto.png)

### Emission Factors Table
![Emission Factors Table](https://github.com/GunelXelilli/Eco-Travel-Data-Warehouse-PostgreSQL-Project-/blob/main/emission-factorsphoto.png)

### Offset Projects Table
![Offset Projects Table](https://github.com/GunelXelilli/Eco-Travel-Data-Warehouse-PostgreSQL-Project-/blob/main/offset-projectsphoto.png)

### Contributions Table
![Contributions Table](https://github.com/GunelXelilli/Eco-Travel-Data-Warehouse-PostgreSQL-Project-/blob/main/Contributionsphoto.png)








