# Google Play Store Apps Dataset Analysis

## Dataset Overview
This dataset contains information about Android applications available on the Google Play Store, including ratings, installs, reviews, price, category, and content rating.

## Business Problem
Can we predict whether an app will receive a high user rating based on its characteristics? Understanding these factors can help developers improve app quality and user satisfaction.

## Machine Learning Problem
Classification

### Justification
The problem can be framed as classifying apps into High Rated and Low Rated categories using their attributes.

## Target Variable
Rating_Category (derived from the Rating column)

## Key Features
- Category
- Reviews
- Installs
- Size
- Type
- Price
- Content Rating
- Genres

## Exploratory Data Analysis (EDA)

The following exploratory analyses were performed using Pandas:

- Dataset Overview
- Dataset Shape (Rows & Columns)
- Column Information
- Data Types Analysis
- Missing Value Analysis
- Summary Statistics
- Target Variable Exploration (App Ratings)
- Feature Analysis (Category, Reviews, Installs, Price, Type, Content Rating)
- Basic Data Visualization
- Key Observations and Insights  

## Three Key Observations

### Observation 1

Most applications in the dataset are free.

### Observation 2

Most app ratings are between 4.0 and 4.5.

### Observation 3

Several columns contain missing values and require preprocessing before model training.

## Conclusion

The dataset exploration helped identify the structure, quality, and important features of the Google Play Store Apps dataset. By analyzing the data, a relevant business problem and a suitable machine learning approach were identified. This exploratory analysis provides the groundwork for building predictive models and extracting meaningful insights from the dataset.
