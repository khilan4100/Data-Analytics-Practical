# 📊 Practical Report

## Categorization of Data Based on Organization, Format, and Structure to Determine Analytical Suitability

------------------------------------------------------------------------

## 👨‍🎓 Subject: Data Analytics

## 📅 Practical No.: 1

## 🎯 Objective

To classify data based on its structure, format, and organization, and
determine its suitability for analytical processing.

------------------------------------------------------------------------

# 📖 1. Introduction

In Data Analytics, understanding the type of data is the first and most
important step before performing analysis.\
Different types of data require different tools, preprocessing
techniques, and analytical methods.

Data can be categorized based on: - Structure\
- Format\
- Organization

This classification helps determine whether the data is directly
suitable for analysis or requires preprocessing.

------------------------------------------------------------------------

# 🏗 2. Categorization Based on Structure

## 🔹 2.1 Structured Data

### Definition

Structured data is highly organized data stored in rows and columns.

### Examples

-   Excel files (.xlsx)\
-   CSV files (.csv)\
-   SQL Databases\
-   Relational Database Tables

### Analytical Suitability

Highly suitable for analysis. It can be directly used in tools like
Python, R, SQL, Power BI, and Tableau.

------------------------------------------------------------------------

## 🔹 2.2 Semi-Structured Data

### Definition

Semi-structured data does not follow a strict tabular format but
contains tags or hierarchical structure.

### Examples

-   JSON files\
-   XML files\
-   API responses\
-   NoSQL database records

### Analytical Suitability

Suitable after preprocessing. Data must be cleaned and converted into
tabular format before analysis.

------------------------------------------------------------------------

## 🔹 2.3 Unstructured Data

### Definition

Unstructured data does not have a predefined format or schema.

### Examples

-   Social media posts\
-   Emails\
-   Images\
-   Audio files\
-   Videos

### Analytical Suitability

Not directly suitable. Requires advanced techniques like: - Natural
Language Processing (NLP)\
- Image Processing\
- Machine Learning

------------------------------------------------------------------------

# 🗂 3. Categorization Based on Format

  Format         Example              Analytical Suitability
  -------------- -------------------- ------------------------
  CSV            sales.csv            Highly Suitable
  Excel          data.xlsx            Suitable
  SQL Database   MySQL / PostgreSQL   Highly Suitable
  JSON           api_response.json    Needs preprocessing
  TXT            comments.txt         Requires cleaning
  Image          photo.jpg            Requires ML tools

------------------------------------------------------------------------

# 🏢 4. Categorization Based on Organization

## Tabular Organization

-   Data stored in rows and columns\
-   Example: Excel sheets\
-   Highly suitable

## Hierarchical Organization

-   Parent-child relationship\
-   Example: JSON, XML\
-   Needs transformation

## Network Organization

-   Graph-based structure\
-   Example: Social network data\
-   Requires graph analytics tools

## Free-Text Organization

-   Paragraph-based data\
-   Example: Reviews, blogs\
-   Needs NLP processing

------------------------------------------------------------------------

# 🔍 5. Comparison of Data Types

  Type              Structure Level   Ease of Analysis   Tools Required
  ----------------- ----------------- ------------------ ---------------------
  Structured        High              Easy               Excel, SQL, Python
  Semi-Structured   Medium            Moderate           Python, JSON Parser
  Unstructured      Low               Complex            NLP, ML, AI Tools

------------------------------------------------------------------------

# 🧪 6. Practical Implementation (Python Example)

``` python
import pandas as pd

# Structured Data Example
structured_data = pd.read_csv("sales.csv")
print("Structured Data Sample:")
print(structured_data.head())

# Semi-Structured Data Example
semi_structured_data = pd.read_json("sample.json")
print("Semi-Structured Data Sample:")
print(semi_structured_data.head())
```

------------------------------------------------------------------------

# 📊 7. Conclusion

Understanding data types is essential before performing analysis.

-   Structured data is the easiest and most suitable for analysis.\
-   Semi-structured data requires preprocessing.\
-   Unstructured data needs advanced techniques like NLP and Machine
    Learning.

Categorizing data based on structure, format, and organization helps
determine the appropriate analytical tools and methods.

------------------------------------------------------------------------

# 📌 Learning Outcome

After completing this practical, we understood: - Different types of
data classification\
- The importance of data structure in analytics\
- How analytical suitability depends on data format\
- The need for preprocessing in semi-structured and unstructured data
