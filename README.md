# 🎬 Netflix Content Analysis and Business Growth Insights

## 📖 Project Overview

Netflix is one of the world's most popular streaming platforms, boasting over 222 million subscribers worldwide as of 2021. With an extensive catalog of over 10,000 movies and TV shows, Netflix continuously strives to understand its global audience and improve its content offerings. This project analyzes Netflix's data to provide insights on content types, trends, and opportunities to help guide production and growth strategies.

## 🧩 Business Problem

Netflix aims to leverage data-driven insights to decide:
1. **Which types of shows/movies to produce** to appeal to various audiences.
2. **How to expand and grow the business** in different countries.

## 📊 Dataset

- **Dataset Link**: [netflix.csv](https://drive.google.com/file/d/13gcL4rOqhNLH9jO9JRXn9ZuLBiWs9juc/view?usp=sharing)

### Dataset Attributes:
- **show_id**: Unique identifier for each Movie/TV Show
- **type**: Movie or TV Show
- **title**: Title of the Movie/TV Show
- **director**: Director of the Movie
- **cast**: Cast members
- **country**: Country of production
- **date_added**: Date it was added on Netflix
- **release_year**: Release year
- **rating**: TV rating
- **duration**: Duration in minutes (movies) or number of seasons (TV shows)
- **listed_in**: Genre(s)
- **description**: Summary of the content

## 📝 Analysis Approach and Hints

This analysis is goal-oriented, focusing on answering critical business questions:
1. **Content Type by Country**: Understanding the types of content popular in different regions.
2. **Trends in Releases**: Examining the changes in movie releases over the last 20–30 years.
3. **Movies vs. TV Shows**: Identifying trends in Netflix’s focus on content type over time.
4. **Optimal Release Time**: Analyzing the best time of year to launch a new show.
5. **Actor/Director Analysis**: Investigating the most prominent actors and directors in Netflix's catalog.
6. **Regional Content Focus**: Understanding which countries have the most unique or diverse content.

**Recommendation Goal**: All recommendations must be data-backed, simple, and accessible to business executives with minimal technical jargon.

## 🔍 Steps for Analysis

1. **Data Exploration**:
   - Examined data structure, types, and a statistical summary.
   - Detected missing values, outliers, and performed necessary preprocessing.
   - Converted categorical attributes to 'category' type where appropriate.

2. **Content Trends**:
   - **Univariate Analysis**: Used distplots, histograms, and countplots to explore individual attributes like `release_year` and `type`.
   - **Bivariate Analysis**: Used boxplots and histograms to investigate relationships (e.g., country vs. content type).
   - **Time-based Analysis**: Examined release year trends to see shifts in content focus over the years.
   - **Actor/Director Analysis**: Analyzed top actors and directors by content type.

3. **Regional Analysis**:
   - Used contingency tables to analyze marginal and conditional probabilities by country and content type.
   - Explored content variety and popular genres per country, providing insights into localized tastes.

4. **Correlation Analysis**:
   - Visualized correlations between features such as `duration`, `rating`, and `release_year` using heatmaps and pairplots.

## 📈 Business Insights and Recommendations

1. **Key Patterns Observed**:
   - Notable trends in content type preferences by country.
   - Shifts toward more TV show releases in recent years.
   - Significant regional interest in certain genres, useful for targeted content production.

2. **Actionable Recommendations**:
   - **Content Focus by Region**: Increase production of popular genres for each region.
   - **Strategic Release Planning**: Launch new content during high-demand periods based on past trends.
   - **Talent-Based Promotion**: Highlight popular actors/directors for promotional campaigns in relevant markets.

## 🎯 Conclusion

This analysis provides actionable insights for Netflix to optimize its content strategy, enhance regional focus, and improve audience satisfaction through data-driven recommendations.

## 🚀 Future Scope

- Expand on actor/director analysis by exploring viewer sentiment and ratings.
- Incorporate engagement metrics to further refine content recommendations.
- Apply clustering techniques for deeper insights into audience segmentation.

## 📧 Contact

For more information or collaboration opportunities, reach out at:

- **Email**: adharshreddy.c@gmail.com
- **LinkedIn**: [adharshreddyc](https://www.linkedin.com/in/adharshreddyc/)
