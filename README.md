# Recipe Analysis 🍽️✨

Welcome to **Recipe Analysis** – a data-driven project showcasing data cleaning, exploratory data analysis (EDA), and a dynamic recommendation system using the **EpiRecipes dataset** from [Kaggle](https://www.kaggle.com/datasets/hugodarwood/epirecipes). This project leverages visual storytelling with Tableau and a comprehensive video presentation.

---

## Video Explanation 🎥

For a detailed walkthrough of the project, including the methodology, insights, and visualizations, click the image below to watch the video:

[![Watch the video](http://img.youtube.com/vi/nTW0CzUH6-o/0.jpg)](https://youtu.be/nTW0CzUH6-o?si=4c2i3l_MmVjmXMm6)

---

## Table of Contents 📚

1. [Objective](#objective)
2. [Dataset](#dataset)
3. [Project Structure](#project-structure)
4. [Tasks Overview](#tasks-overview)
   - [Task 1: Data Cleaning and Preprocessing](#task-1-data-cleaning-and-preprocessing)
   - [Task 2: Exploratory Data Analysis (EDA)](#task-2-exploratory-data-analysis-eda)
   - [Task 3: Recommendation System](#task-3-recommendation-system)
5. [Tableau Dashboard](#tableau-dashboard)
6. [Results and Insights](#results-and-insights)
7. [Conclusion](#conclusion)
8. [Installation and Usage](#installation-and-usage)
9. [License and Acknowledgments](#license-and-acknowledgments)

---

## Objective 🎯

This project aims to demonstrate proficiency in:
- **Data Cleaning & Preprocessing:** Efficiently cleaning and structuring large datasets.
- **Exploratory Data Analysis (EDA):** Extracting actionable insights and telling a story with data.
- **Recommendation System:** Implementing a collaborative filtering-based recommendation engine.
- **Visual Storytelling:** Creating compelling visualizations with Tableau and a detailed video presentation.

---

## Dataset 📊

The **EpiRecipes dataset** contains over 20,000 recipes enriched with ratings, nutritional information, and categorical features like seasonality, meal type, and dietary restrictions. Sourced from [Kaggle](https://www.kaggle.com/datasets/hugodarwood/epirecipes), this dataset provides a rich canvas for culinary analysis.

- **Dataset Link:** [Kaggle - EpiRecipes Dataset](https://www.kaggle.com/datasets/hugodarwood/epirecipes)

---

## Project Structure 🗂️

```bash
Recipe-Analysis/
│
├── epi_r.csv                      # Main dataset 
├── full_format_recipes.json       # Original dataset with detailed recipe info
│
├── notebook.ipynb                 # Jupyter Notebook for analysis
│
├── Dashboard.twb                  # Tableau Dashboard file
│
├── README.md                      # Project Overview (This File)
└── LICENSE                        # License Information
```

---

## Tasks Overview 📝

### Task 1: Data Cleaning and Preprocessing
- **Handling Missing Values:** Identify and impute missing data.
- **Removing Duplicates:** Eliminate redundant records.
- **Encoding Categorical Features:** Transform categorical data using binary/dummy encoding.
- **Feature Engineering:** Create new features such as ingredient length and preparation time.

*Output:* A clean and structured dataset ready for analysis.

### Task 2: Exploratory Data Analysis (EDA)
Key insights include:
- **Ingredient Trends:** Identify common ingredients in high-rated recipes.
- **Seasonal Patterns:** Analyze recipe trends across different seasons.
- **Meal Type Analysis:** Examine preferences for breakfast, lunch, dinner, etc.
- **Nutritional Distribution:** Study the spread of calories, protein, fat, and sodium.
- **Preparation vs. Rating:** Explore the relationship between preparation time and recipe ratings.

Visualizations were crafted in **Tableau** for engaging storytelling.

### Task 3: Recommendation System
A recommendation engine was developed using collaborative filtering techniques to:
- **Personalize Recommendations:** Suggest recipes based on user preferences and dietary restrictions.
- **Leverage Recipe Similarity:** Recommend recipes similar to those highly rated by users.

Built with Python libraries (including `pulp`), this system offers personalized culinary suggestions.

---

## Tableau Dashboard 📈

A comprehensive Tableau Dashboard was created to visualize key insights such as:
- **Top-Rated Recipes**
- **Nutritional Content Analysis**
- **Seasonal Recipe Trends**
- **Meal-Type Distributions**

Explore the interactive dashboard to dive deeper into the dataset's story.

---

## Results and Insights 💡

- **Common Ingredients:** Frequent use of ingredients like garlic, onions, and butter.
- **Seasonal Trends:** Lighter recipes dominate in summer, while heartier meals appear in fall and winter.
- **Nutritional Analysis:** High-rated recipes often balance moderate calorie and fat levels.
- **User Preferences:** Quick and easy recipes tend to receive higher ratings.

---

## Conclusion 🏁

This project highlights my ability to:
- Clean and preprocess large datasets.
- Extract meaningful insights through comprehensive EDA.
- Develop a practical recommendation system.
- Present data-driven stories using impactful visualizations.

These skills demonstrate a strong foundation in data analysis and visualization, making this project a robust case study in the culinary domain.

---

## Installation and Usage ⚙️

1. **Clone the repository:**

```bash
git clone https://github.com/Ria2810/Recipe-Analysis.git  
cd Recipe-Analysis  
```

2. **Install necessary dependencies:**

```bash
pip install -r requirements.txt  
```

3. **Run the Jupyter Notebook for analysis:**

```bash
jupyter notebook  
```

---

## License and Acknowledgments 📄🙏

- **License:** This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
- **Acknowledgments:**  
  - **Kaggle:** For providing the rich dataset.
  - **Tableau:** For the powerful visualization tools.
  - **Community & Mentors:** For their guidance and inspiration.

---

Happy analyzing and cooking up some data insights! 🍳📊
