# Newsfeed Analysis Project

## Overview

This project aims to analyze newsfeed data to derive insights on user engagement, content popularity, and trends over time. Using Tableau for visualization, we have developed dashboards to represent key metrics, trends, and patterns in user interactions with news content.

## Case Description

### Overview
In this Newsfeed Analysis in Tableau project, you’ll tackle a real-world case and gain hands-on experience optimizing a website’s newsfeed feature for maximum user engagement. Dive deep into a real-life database, perform data analysis in Tableau, and unearth crucial insights that can enhance your professional portfolio and skillset.

### Objective
Your main goal is to generate graphs that analyze users’ interaction patterns with the 365 platform’s Newsfeed service. For this purpose, you must craft a data visualization in Tableau that captures critical findings from 01-01-2023 to 05-31-2023. Build this Tableau dashboard from scratch, utilizing it to deduce necessary conclusions and recommend potential refinements.

### The Challenge
A newsfeed is a part of a website that constantly updates with new content, showing the latest news or activities. This feature facilitates real-time discoveries and encourages user engagement by presenting fresh content each time the user accesses the platform.

The 365 platform’s Newsfeed offers a mix of automated and manual posts. Automated entries showcase students’ milestones, such as completing an award card collection or earning a certificate of achievement. On the other hand, manual entries are texts created by students to share insights or opinions with the community.

The aim of this Newsfeed Analysis in Tableau project is to determine which type resonates more with our audience and identify potential issues with these features, along with suggestions for enhancements. The task is to create several visualizations giving crucial information about the newsfeed and how the users react to it.

Drawing from your findings, you can create a strategy to optimize the newsfeed service, ensuring it’s engaging and encourages prolonged platform usage—fostering a vibrant online community and, ultimately, influencing course subscriptions and renewals.

## Features

- **User Engagement Analysis**: Visualizations showing user engagement across different content categories.
- **Content Performance**: Comparison of different types of news articles by views, reactions, and shares.
- **Trend Analysis**: Insights on how engagement evolves over time, helping to identify seasonal or topical trends.

## Tools and Technologies

- **Tableau**: Used for creating interactive dashboards and visual analytics.
- **Data Source**: The dataset consists of newsfeed interaction metrics such as views, clicks, reactions, and shares.

## Visualizations

The Tableau workbook includes the following key dashboards:

1. **User Engagement Overview**: Highlights user interactions across different content types. This dashboard includes:
   - **Average Likes per Post**: A bar chart showing the average likes received by each post subtype. It is evident that Level-type and Collection-type posts are the least popular, with an average of around 0.02 likes per post. Specifically:
     - **Collection**: Out of 9,376 posts, only 170 received likes.
     - **Level**: Out of 22,313 posts, only 422 received likes.


<img width="600" alt="User Engagement Overview Collection" src="Dashboard Snippets/User Engagement Overview Collection.png">


<img width="600" alt="User Engagement Overview Levels" src="Dashboard Snippets/User Engagement Overview Levels.png">


2. **Subtype Post Distribution**: Displays the most and least frequent post types based on user engagement metrics. The key visualizations include:
   - **Frequency of Post Types**: A bar chart showing the frequency of each post type. The Level-type posts are the most prevalent, appearing 22,313 times, whereas the Career Track Certificate posts are the least frequent, with only 144 instances. Manual Text posts are the second least common with 150 examples.


<img width="600" alt="Subtyp Post Distribution" src="Dashboard Snippets/Subtype Post Distribution.png">


3. **Newsfeed User Engagement**: Shows trends in user engagement over time, helping to understand when users are most active. The visualizations include:
   - **Engagement Rate Calculation**: This graph calculates the proportion of visitors who engaged with the newsfeed. By dividing the number of active users (405) by the overall visitors (3956) and multiplying by 100, we get an engagement rate of 10%.


<img width="600" alt="Newsfeed USer Engagement" src="Dashboard Snippets/Newsfeed User Engagement.png">


4. **Post Type Analysis**: Highlights the relationship between the frequency of post types and user engagement. Key findings include:
   - **Level-type Posts Dominance**: Level-type posts dominate the newsfeed, surpassing all other subtypes. Despite their high frequency, these posts—alongside Collection posts—generate minimal user interest. This suggests that Level-type posts might be saturating the newsfeed with content users don't find compelling, potentially diminishing their overall experience with the feature.
   - **Recommendations**: Reevaluating how Level-type posts are generated and reducing their prevalence on the newsfeed could help improve engagement. More engaging posts, such as those that receive higher likes and interactions, should be prioritized.

## Tableau Public Link

You can explore the interactive version of the dashboards on Tableau Public: [Newsfeed Analysis Dashboard](https://public.tableau.com/app/profile/kaushik.rohida6402/viz/NewsfeedAnalysisDashboard_17305941019910/NewsfeedAnalysisDashboard)

## Getting Started

To explore the analysis:

1. Clone this repository to your local machine.
2. Open the `.twbx` file using Tableau Desktop.
3. Review the available dashboards to understand key insights.


## Project Structure

- **newsfeed_analysis.twbx**: Tableau workbook containing the visual analysis.
- **README.md**: Documentation file.

## Insights and Findings

- **Least Favored Post Subtype**: The Level-type and Collection-type posts are the least favored, with an average of 0.02 likes per post. This indicates a lack of interest in these post types.
- **Frequency of Post Types**: Level-type posts are the most prevalent, while Career Track Certificate posts are the least common.
- **Engagement Rate**: The engagement rate of the newsfeed is 10%, indicating that a majority of users do not actively interact with the posts.
- **Content Saturation**: Level-type posts are saturating the newsfeed, which may diminish user interest. Reducing their frequency and focusing on more engaging content could enhance user experience.

## Conclusion

The newsfeed analysis provides valuable insights into user engagement behavior, content popularity, and temporal trends. Key conclusions include:

- **Content Strategy Optimization**: Level-type and Collection-type posts should be curtailed to avoid content saturation, while more engaging posts should be prioritized to enhance user interaction.
- **Timing of Content Releases**: Publishing content during weekends and in the morning hours can significantly boost engagement levels.
- **Content Type Focus**: Increasing the visibility of engaging post types, such as those with high likes, can help maintain user interest and improve the overall newsfeed experience.

## Future Work

- Integrate additional data sources for a more holistic analysis.
- Develop predictive models to forecast content performance.
- Explore user segmentation to understand different audience preferences and tailor content accordingly.


## Contact

For questions or suggestions, please contact [Kaushik Rohida](mailto:rohidakaushik@gmail.com).