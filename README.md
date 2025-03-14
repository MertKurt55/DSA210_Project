### **Investigating the Impact of Digital Platforms on the Cinema Industry**  

#### **Motivation**  
The rapid rise of streaming platforms like Netflix has transformed the film industry. Traditional cinema has faced challenges as more people choose to watch movies on digital platforms instead of in theaters. This project aims to explore how these platforms have influenced movie production, particularly in terms of budgets, genres, and audience reception. By comparing data from both traditional cinema and streaming platforms, I hope to gain insights into how the industry is evolving.  


#### **Data Collection**  
To analyze this topic, I have collected data from **Kaggle**, which provides publicly available datasets on movies and streaming platforms. The two datasets I will be using are:  

1. **Netflix Top Rated Movies and TV Shows (2020-2022)**  
   - **Source:** Kaggle (by The Devastator)  
   - **Description:** This dataset contains information on over 600 movies and TV shows from Netflix, including release year, runtime, genres, production country, IMDb scores, and ratings.  
   - **Access:** [Netflix Top Rated Movies and TV Shows - Kaggle](https://www.kaggle.com/datasets/thedevastator/netflix-top-rated-movies-and-tv-shows-2020-2022)  

2. **Movie Industry Dataset**  
   - **Source:** Kaggle (by Daniel Grijalva)  
   - **Description:** This dataset includes data on over 6,800 movies from 1986 to 2016, containing details such as budget, production company, country, director, genre, gross revenue, and IMDb ratings.  
   - **Access:** [Movie Industry - Kaggle](https://www.kaggle.com/datasets/danielgrijalvas/movies)  

**Additional Data Enrichment:**  
- **IMDb Ratings API:** I may collect updated IMDb ratings for movies in both datasets.  
- **Box Office Revenue Data:** If needed, I will look at sources like Box Office Mojo or The Numbers to compare box office performance with streaming performance.  


#### **Analysis Plan**  

1. **Data Cleaning & Integration**  
   - Remove duplicates and missing values.  
   - Standardize column formats (e.g., budget in USD, runtime in minutes).  
   - Merge datasets where possible using movie titles and release years.  

2. **Exploratory Data Analysis (EDA)**  
   - **Compare budgets:** How do Netflix movie budgets compare to traditional studio budgets?  
   - **Analyze trends:** What genres are more common on streaming platforms vs. traditional cinema?  
   - **Audience reception:** Do Netflix original movies perform better or worse in terms of IMDb ratings?  

3. **Visualization & Statistical Analysis**  
   - Use graphs to show trends in movie budgets over time.  
   - Identify correlations between budget size and IMDb ratings.  
   - Compare box office revenue vs. streaming success metrics.  


