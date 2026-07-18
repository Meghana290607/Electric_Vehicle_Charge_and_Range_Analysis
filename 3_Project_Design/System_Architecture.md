# System Architecture

## Project Title

Visualization Tool for Electric Vehicle Charge and Range Analysis

---

# 1. Introduction

The system architecture illustrates the complete workflow of the project, showing how raw electric vehicle data is transformed into interactive dashboards and made available to users through a Flask web application.

The architecture integrates multiple technologies, including MySQL for database management, Tableau for visualization, and Flask for web deployment, ensuring a scalable and user-friendly analytics platform.

---

# 2. Architecture Components

## Data Source

The project begins with a dataset containing detailed information about electric vehicles and charging stations.

The dataset includes:

- Brand
- Model
- Battery Capacity
- Driving Range
- Charging Time
- Charging Speed
- Top Speed
- Price
- Body Style
- Powertrain
- Charging Station Details

---

## Data Preprocessing

The collected data undergoes preprocessing to improve quality and consistency.

The preprocessing activities include:

- Removing duplicate records
- Handling missing values
- Correcting inconsistent entries
- Standardizing column names
- Formatting numerical values

---

## Database Layer

The cleaned dataset is imported into MySQL, where it is stored in structured tables. SQL queries are used to retrieve relevant information for visualization.

---

## Visualization Layer

The MySQL database is connected to Tableau Public.

Interactive worksheets are created and combined into dashboards and stories, enabling users to analyze EV data using charts, maps, graphs, and filters.

---

## Web Application Layer

A Flask web application is developed to embed the Tableau Dashboard and Tableau Story.

The application provides the following pages:

- Home
- About
- Dashboard
- Story
- Team
- Contact

---

## End User

Users access the dashboard through the Flask web application and interact with the visualizations to explore EV data.

---

# 3. Architecture Flow

EV Dataset

↓

Data Cleaning

↓

MySQL Database

↓

SQL Queries

↓

Tableau Connection

↓

Interactive Worksheets

↓

Dashboard

↓

Tableau Story

↓

Flask Web Application

↓

End User

---

# 4. Advantages

- Modular architecture
- Easy maintenance
- Scalable design
- Interactive visualization
- Fast data retrieval
- Responsive web interface

---

# 5. Conclusion

The system architecture provides an efficient framework for collecting, processing, visualizing, and presenting electric vehicle data through an interactive Business Intelligence platform.
