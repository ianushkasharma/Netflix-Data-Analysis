# 📊 Netflix Data Analysis

This project performs exploratory data analysis (EDA) and visualization on the [Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows) using Python. It provides insights into content types, ratings, durations, release trends, and country-wise distributions.

## 🔍 Project Objective

Analyze the Netflix content dataset to:
- Understand the distribution between Movies and TV Shows
- Explore content rating proportions
- Visualize release trends over time
- Analyze movie durations
- Identify top content-producing countries
- Compare movie and TV show trends year-over-year

---

## 📁 Dataset

- **Source**: [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **File Used**: `Netflix_Titles.csv`

---

## 🧰 Tools and Libraries

- Python 3.x
- `pandas` for data manipulation
- `matplotlib` for data visualization

---

## 📊 Visualizations

1. **Movies vs TV Shows**
   - Bar chart showing the count of each content type.

2. **Content Rating Distribution**
   - Pie chart representing the proportion of each rating (e.g., TV-MA, PG-13, etc.).

3. **Releases Over the Years**
   - Line plot showing how the number of titles has changed over the years.

4. **Movie Duration Distribution**
   - Histogram visualizing the distribution of movie durations in minutes.

5. **Release Year vs Number of Shows**
   - Scatter plot displaying the number of releases per year.

6. **Top 10 Countries by Number of Shows**
   - Horizontal bar chart of the top countries contributing content.

7. **Movies vs TV Shows by Year**
   - Dual subplot showing how movies and TV shows were released year-wise.

---

## 🧹 Data Cleaning

- Dropped rows with missing values in critical columns: `type`, `release_year`, `rating`, `country`, `duration`.

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/ianushkasharma/netflix-data-analysis.git
   cd netflix-data-analysis
2. Install dependencies:
   ```bash
   pip install pandas matplotlib
3. Run the script:
   ```bash  
   python netflix_analysis.py

---

## 💡 Future Improvements

- Use seaborn or plotly for enhanced visuals

- Add interactivity with Streamlit or Dash

- Perform genre-wise or actor-wise analysis

---

## 📌 License

This project is for educational purposes.

---

## 🙌 Acknowledgements

Dataset from Kaggle by Shivam Bansal

---
