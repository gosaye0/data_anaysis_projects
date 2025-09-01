# E-commerce Customer Behavior Analysis

## Project Overview
Analysis of Brazilian e-commerce data to understand customer behavior patterns and provide business insights.

## Dataset
- Source: Brazilian E-Commerce Public Dataset by Olist
- Size: 100k+ orders from 2016-2018
- Features: Customer data, order details, product information, reviews

## Business Questions
1. What are the key customer segments?
2. Which factors drive customer satisfaction?
3. What are seasonal purchasing patterns?
4. Which products/categories perform best?

## Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebooks
- Git/GitHub
## Data Processing Pipeline

### Data Quality Assessment
- Systematic evaluation of 8 datasets
- Memory optimization  
- Business logic validation preventing analysis errors

### Cleaning Methodology
- **Missing Values**: Business-driven strategies rather than blanket imputation
- **Data Types**: Optimized for memory efficiency and analytical accuracy
- **Master Dataset**: Analysis-ready merged dataset with proper aggregations

### Key Processing Decisions
- Dropped orders missing critical approval dates 
- Implemented datetime parsing with error handling
- Generated order-level aggregations maintaining analytical granularity

## Project Status
🚧 In Progress