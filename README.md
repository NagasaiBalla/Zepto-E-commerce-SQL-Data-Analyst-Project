# Zepto-E-commerce-SQL-Data-Analyst-Project

## Project Overview

This project demonstrates a complete SQL-based data analysis workflow using a real-world Zepto e-commerce inventory dataset.

The objective is to simulate how Data Analysts work with raw inventory data to perform:

* Database Design
* Data Exploration
* Data Cleaning
* Business Analysis
* Insight Generation

## Tools Used

* PostgreSQL
* pgAdmin
* SQL
* GitHub

## Dataset

The dataset contains product inventory information scraped from Zepto's product catalog.

### Key Columns

* sku_id
* category
* name
* mrp
* discountPercent
* discountedSellingPrice
* availableQuantity
* weightInGms
* outOfStock
* quantity

## Project Workflow

### 1. Database Creation

Created a relational database schema using PostgreSQL.

### 2. Data Exploration

* Row counts
* Null value analysis
* Product category analysis
* Inventory status analysis

### 3. Data Cleaning

* Removed invalid pricing records
* Converted paise values into rupees

### 4. Business Analysis

* Top discounted products
* Out-of-stock high-value products
* Revenue estimation by category
* Discount trend analysis
* Price-per-gram analysis
* Inventory weight analysis

## Key SQL Concepts Used

* Aggregations
* GROUP BY
* HAVING
* CASE Statements
* Data Cleaning
* Sorting and Ranking
* Filtering
* Aggregate Functions

## Repository Structure

dataset/
sql/
screenshots/
README.md

## Author

Balla Naga Sai

LinkedIn: https://www.linkedin.com/in/ballanagasai/
