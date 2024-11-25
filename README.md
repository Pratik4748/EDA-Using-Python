# **Netflix Data Analysis**

## **Project Overview**  
This project analyzes Netflix's dataset to uncover trends in content, including movies and TV shows. The analysis focuses on content types, genres, countries, release years, ratings, and more.

---

## **Dataset**  
- **Source**: [Netflix Dataset](https://www.kaggle.com/code/chirag9073/netflix-data-analysis)  
- Contains information about:  
  - Type (Movie/TV Show)  
  - Title, Director, and Cast  
  - Country of Origin  
  - Release Year and Date Added  
  - Content Rating and Duration  
  - Genres (Categories)  

---

## **Key Highlights**  
### **1. Data Cleaning**  
- Removed duplicates and handled missing values in columns like `director`, `cast`, and `country`.  
- Converted `date_added` to proper datetime format for analysis.

### **2. Exploratory Data Analysis (EDA)**  
- **Content Type**:  
  - Movies constitute ~70% of Netflix's library.  
- **Top Genres**:  
  - Popular genres include International Movies, Dramas, and Comedies.  
- **Country Trends**:  
  - The USA dominates content production, followed by India and the UK.  
- **Release Year**:  
  - Content production peaked in 2018.  
- **Average Duration**:  
  - Movies average ~90 minutes, while TV Shows have ~2 seasons.  
- **Ratings**:  
  - TV-MA and TV-14 are the most common ratings.  

### **3. Visualizations**  
- Distribution of Movies vs. TV Shows (pie chart and bar graph).  
- Top 10 genres and top countries by content.  
- Trends in release years (line chart).  
- Word clouds for countries, cast, directors, and genres.

---

## **Tools & Libraries Used**  
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, WordCloud  

---

## **How to Run**  
1. Clone this repository:  
   ```bash
   git clone https://github.com/Pratik4748/EDA-using-python.git
2. Navigate to the project directory.
3. Install required dependencies:
    ```bash
   pip install -r requirements.txt
4. Run the Jupyter Notebook or Python scripts to view the analysis.

## **Results**
- This analysis provides insights into Netflix's content library, helping to understand trends in global entertainment.



