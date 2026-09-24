# Simple Data Filtering

## Project Description

This project demonstrates how to create student records and filter student data based on different conditions using Python.

The project uses a list of dictionaries to store student information such as:

- Name
- Marks
- Age
- Department

## Objective

To understand how conditional statements can be used to filter structured data.

## Tools Used

- Python
- Jupyter Notebook
- Pandas

## Features

- Create student records using Python dictionaries
- Filter students based on marks
- Filter students based on department
- Apply multiple filtering conditions
- Filter data using Pandas DataFrame

## Filtering Examples

### 1. Students with Marks >= 80

Students are filtered based on their marks.

### 2. ENTC Students with Marks >= 80

Students are filtered using two conditions:

- Department = ENTC
- Marks >= 80

### 3. Students Younger Than 21 with Marks >= 75

Students are filtered using age and marks conditions.

## Files

| File | Description |
|------|-------------|
| Simple_Data_Filtering.ipynb | Jupyter Notebook containing the complete Python implementation |
| student_records.csv | Student dataset used in the project |

## Sample Student Data

| Name | Marks | Age | Department |
|------|------:|----:|------------|
| Aarav | 85 | 20 | ENTC |
| Priya | 72 | 21 | Computer |
| Rahul | 91 | 20 | ENTC |
| Sneha | 64 | 22 | Mechanical |
| Aditya | 78 | 19 | Computer |
| Neha | 88 | 21 | ENTC |
| Rohan | 55 | 20 | Civil |
| Kavya | 95 | 19 | Computer |

## Interview Questions

### What is data filtering?

Data filtering is the process of selecting only the records that satisfy a specific condition from a dataset.

### How would you filter a Pandas DataFrame?

A Pandas DataFrame can be filtered using Boolean conditions.

Example:

```python
df[df['marks'] >= 80]
