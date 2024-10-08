# Recipe Analysis

This project is designed to showcase data cleaning, exploratory data analysis (EDA), and a recommendation system using the **EpiRecipes dataset** sourced from [Kaggle](https://www.kaggle.com/datasets/hugodarwood/epirecipes ). The focus of the project is to derive actionable insights and provide visual storytelling with the help of Tableau and a video presentation.

## Table of Contents

1. [Objective](#objective)
2. [Dataset](#dataset)
3. [Project Structure](#project-structure)
4. [Tasks Overview](#tasks-overview)
    - Task 1: Data Cleaning and Preprocessing
    - Task 2: Exploratory Data Analysis (EDA)
    - Task 3: Recommendation System
5. [Tableau Dashboard](#tableau-dashboard)
6. [Video Explanation](#video-explanation)
7. [Results and Insights](#results-and-insights)
8. [Conclusion](#conclusion)
9. [Installation and Usage](#installation-and-usage)

---

## Objective

This assignment aims to evaluate the candidate’s ability to:

- Clean, analyze, and preprocess data efficiently.
- Explore the dataset and generate meaningful insights through EDA.
- Apply creativity in developing a recommendation system.
- Use visualizations to communicate insights clearly and concisely.
  
The focus is on demonstrating a strong understanding of data analysis fundamentals, storytelling with data, and proficiency in various data analysis tools.

---

## Dataset

The **EpiRecipes dataset** consists of over 20,000 recipes along with their ratings, nutritional information, and various categorical features like seasonality, meal type, and dietary restrictions. This dataset was sourced from Kaggle and provides a rich resource for analysis.

- Dataset: [Kaggle - EpiRecipes Dataset](https://www.kaggle.com/datasets/hugodarwood/epirecipes )

---

## Project Structure
```
Recipe-Analysis/
│
├── data/
│   └── epi_r.csv                # Main dataset (cleaned and preprocessed)
│   └── full_format_recipes.json  # Original dataset with detailed recipe info
│
├── notebook.ipynb                # Jupyter notebook
│
├── Tableau/
│   └── Recipe_Analysis.twb       # Tableau Dashboard file
│
├── README.md                     # Project Overview (This File)
└── LICENSE                       # License Information
```
---

## Tasks Overview

### Task 1: Data Cleaning and Preprocessing
The first step of the project involved cleaning the dataset to ensure consistency, accuracy, and usability. Key operations include:
- Handling missing values.
- Removing duplicates.
- Encoding categorical features (binary and dummy variables).
- Feature engineering: creating new features like the length of ingredients and directions for each recipe.

**Output**: Clean and structured dataset ready for analysis.

### Task 2: Exploratory Data Analysis (EDA)
In this task, I performed a comprehensive analysis of the dataset, uncovering insights related to:
- Most common ingredients used in high-rated recipes.
- Season-based recipe patterns (spring, summer, fall, winter).
- Meal type preferences (breakfast, lunch, dinner, etc.).
- Nutritional distribution (calories, protein, fat, sodium) across recipes.
- Relationship between recipe rating and preparation time.

These insights were visualized using **Tableau** for better storytelling and interpretation.

### Task 3: Recommendation System
In this final task, I developed a basic recommendation system using collaborative filtering techniques. The goal was to recommend recipes based on:
- User preferences (meal type, dietary restrictions).
- Highly rated recipes similar to user history.

The recommendation engine was built using Python’s machine learning libraries like `pulp` for collaborative filtering.

---

## Tableau Dashboard

I have created a Tableau Dashboard to visualize key insights from the dataset. The dashboard focuses on:
- Top-rated recipes.
- Nutritional content distributions.
- Seasonal recipes.
- Meal-type trends.

---

## Video Explanation

For a detailed walkthrough of the project, including the methodology, insights, and visualizations, you can watch my video explanation [here](https://youtu.be/nTW0CzUH6-o?si=4c2i3l_MmVjmXMm6).

---

## Results and Insights

- **Most Common Ingredients**: Ingredients like garlic, onions, and butter are frequent in highly rated recipes.
- **Seasonal Recipes**: Summer recipes tend to have lighter meals like salads, while fall and winter feature more hearty, warm meals.
- **Nutritional Analysis**: High-rated recipes often have moderate calorie and fat levels, focusing more on balanced ingredients.
- **Quick & Easy Meals**: Recipes that require less preparation time generally receive favorable ratings, reflecting user preference for convenience.

---

## Conclusion

This project highlights my ability to clean and analyze large datasets, extract meaningful insights, and present findings effectively using both Python and Tableau. The recommendation system adds a practical layer by allowing users to find recipes based on personal preferences and high ratings.

---

## Installation and Usage

1. **Clone the repository**:
   ```git clone https://github.com/Ria2810/Recipe-Analysis.git```

2. Install necessary dependencies:
```pip install -r requirements.txt```

3. Run the Jupyter Notebooks to perform data cleaning, EDA, and recommendation system generation:
```jupyter notebook```


