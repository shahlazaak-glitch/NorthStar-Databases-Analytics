# NorthStar Databases and Analytics Coursework

This repository contains the analytical workflows for the Databases and Analytics coursework based on the NorthStar Urban Mobility and Logistics case study.

## Project Overview

NorthStar is facing operational issues such as failed deliveries, customer complaints, service delays, incidents, rising costs and fragmented data systems. This project uses Python, SQL within R, R analytics and MongoDB Atlas to analyse the dataset and propose a more integrated data solution.

## Repository Contents

| File | Description |
|---|---|
| `01_python_data_processing.ipynb` | Python notebook for loading, cleaning, merging and analysing the NorthStar dataset |
| `02_sql_in_r_analysis.ipynb` | R notebook containing SQL queries and R visualisations |
| `03_mongodb_development.ipynb` | Python notebook for MongoDB Atlas connection, NoSQL design, CRUD operations, aggregation and query optimisation |
| `northstar_master_dataset.csv` | Cleaned and integrated master dataset exported from Python |

## Tools Used

- Google Colab
- Python
- Pandas
- NumPy
- Matplotlib
- R
- SQL within R
- sqldf
- ggplot2
- MongoDB Atlas
- PyMongo

## Main Analysis Areas

- Data loading and cleaning
- Dataset integration
- KPI analysis
- Failed delivery analysis
- Complaint analysis
- Cost analysis
- SQL queries in R
- R visualisation
- MongoDB NoSQL database design
- Integrated service case document structure
- CRUD operations
- MongoDB aggregation
- Indexing and query optimisation

## MongoDB Design

A MongoDB database called `northstar_db` was created. The project includes separate collections for orders, deliveries, customers, complaints, incidents, drivers, vehicles, hubs and app events.

An additional nested collection called `integrated_service_cases` was designed to combine related customer, order, delivery, complaint, incident and app-event data into one document. This supports better operational investigation and decision-making.

## Note

Sensitive credentials such as MongoDB connection strings and passwords are not included in this repository.
