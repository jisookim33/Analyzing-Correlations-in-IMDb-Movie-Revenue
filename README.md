# Analyzing Correlations in IMDb Movie Revenue

### 📝 Project Overview
This project explores what factors—such as budget, user score, genre, number of votes, production companies, and release year—are most strongly correlated with movie revenue using data from IMDb. The goal is to gain insights into what contributes to a movie's financial success.

### 📁 Dataset
- **Sourced:** [Kaggle - The Movie Industry](https://www.kaggle.com/datasets/danielgrijalvas/movies))<br />
- **Records: 7,653 movies**
- **Features include:**
  - Title
  - Genre
  - Budget
  - Gross Revenue
  - Score
  - Votes
  - Year
  - Company
  - and more

### 🔑 Key Questions
1. Does a higher budget result in higher revenue?
2. Are scores associated with gross revenue?
3. What other factors are correlated with high revenue?
4. Are certain production companies more successful?
5. Which genres tend to perform best at the box office?
6. Which years produced the most high-grossing movies?
 
### 📈 Methods
This analysis was conducted using **Python**, with the help of key libraries including:

- **Pandas** for data manipulation and cleaning
- **NumPy** for numerical operations (e.g., calculating means)
- **Seaborn** and **Matplotlib** for data visualization

The following steps were performed:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Correlation Analysis (Pearson and Spearman)
- Visualizations using `matplotlib` and `seaborn`



### 📌 Conclusions
- Budget and number of votes show the strongest correlation with gross revenue.
- Scores and production companies show weaker, but still relevant, associations.
- Action, animation, and adventure genres tend to perform best.
- More recent years (2017–2019) have seen the highest average revenues.
