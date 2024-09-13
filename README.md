# Sentiment Analysis of UAE Company News Titles Using Power BI

This project involves the sentiment analysis of news titles for various UAE companies, utilizing Power BI for visualization. The objective is to offer insights into sentiment trends across different companies over time.

**Project Highlights:**

  1. **Data Extraction:**

      - Utilized the GoogleNews Python library to fetch news articles for a predefined list of UAE companies.
      - Extracted data included company names, news titles, and publication dates.

  2. **Data Collection & Cleaning:**

    - Collected news articles for major UAE market entities.
    - Preprocessed text to remove special characters, links, and non-alphanumeric characters.

  3. **Sentiment Analysis:**

    - Employed VADER sentiment analyzer for sentiment scoring.
    - Classified sentiments as positive, negative, or neutral based on predefined thresholds.

  4. **Validation & Testing:**

    - Manually reviewed a sample of news titles to validate sentiment accuracy.
    - Conducted unit and integration tests to ensure the accuracy and functionality of the sentiment analysis and data extraction process.

**Implementation Details:**

  - **Data Extraction:** Used libraries like pandas and GoogleNews, and fetched news articles, storing them in a pandas DataFrame.

  - **Text Cleaning:** Implemented text preprocessing to clean news titles.

  - **Sentiment Analysis:** Calculated sentiment scores and categorized them.

  - **Visualization:** Created various visualizations in Power BI, including time series analysis, stacked bar charts, bar charts, word clouds, and heat maps to illustrate sentiment trends.

**Visualizations:**  

  - **Top Performing Companies:** Bar chart highlighting companies with the highest average sentiment scores.
      ![image](https://github.com/user-attachments/assets/d028d0d1-6883-4e73-b38f-21366a5e8181)


  - **Word Cloud:** Visualization of frequently occurring words in news titles.
      ![image](https://github.com/user-attachments/assets/452c9e2c-d3a4-4abd-876e-e324510a3116)


  - **Heat Map:** Sentiment scores across dates and companies for comprehensive trend analysis.
      ![image](https://github.com/user-attachments/assets/90fc5f5a-71e5-44d4-891c-fe67f61baf77)

     - **Time Series Analysis:** Line chart showing sentiment trends over time for each company.
      ![image](https://github.com/user-attachments/assets/55c32a28-3c89-4240-8e00-0a8a7947a2b2)

- **Comparison:** Stacked bar chart comparing sentiment scores across companies.
      ![image](https://github.com/user-attachments/assets/ff92f41c-7486-4014-ba01-003749c1b1e4)


**Experience Reflection:** This project enhanced my ability to handle data extraction, preprocessing, and sentiment analysis, and provided valuable insights into sentiment dynamics. It also emphasized the importance of error handling and collaboration with stakeholders to ensure accurate and relevant results.
