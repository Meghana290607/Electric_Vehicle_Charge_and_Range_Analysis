# SQL Queries

The following SQL operations were performed:

- SELECT
- WHERE
- ORDER BY
- GROUP BY
- COUNT()
- SUM()
- AVG()
- MAX()
- MIN()
- JOIN

These queries were used to prepare data for Tableau visualizations and generate meaningful insights.

Examples:
#creating Database
create database electric_vehicle;   
#using Database
USE electric_vehicle;      
#creating tables
CREATE TABLE electric_cars (
    Brand VARCHAR(50),
    Model VARCHAR(100),
    AccelSec DECIMAL(4,1),
    TopSpeed_KmH INT,
    Range_Km INT,
    Efficiency_WhKm INT,
    FastCharge_KmH INT,
    RapidCharge VARCHAR(10),
    PowerTrain VARCHAR(20),
    PlugType VARCHAR(50),
    BodyStyle VARCHAR(30),
    Segment CHAR(1),
    Seats INT,
    PriceEuro INT
); 
#retriving data
select *  from evindia;
select * from electriccardata_clean;
select * from electriccardata_clean where powerTrain = 'AWD';
select * from electriccardata_clean where powerTrain = 'AWD' and BodyStyle = 'Sedan';
