# [UDACITY] RECOMMENDATION ENGINE WITH IBM

## Introduction
For this project, I'll look into how users engage with articles on the IBM Watson Studio platform and give suggestions for new articles that I believe they'll enjoy.
![image](https://user-images.githubusercontent.com/88694623/162686610-445fc6ea-e743-4c31-8bfb-f8fec5f67251.png)

### I. Exploratory Data Analysis
I'll need to investigate the data you're working with for the project before providing any advice. I'm going to dive in and see what I can find. Throughout the rest of the notebook, there are some fundamental, essential questions to be answered about the data I'm working with. Before I get into the mechanics of my recommendation system in the later sections, use this area to explore.

### II. Rank Based Recommendations
To begin creating recommendations, I'll look for the most popular articles based on the number of interactions. Because none of the articles have ratings, it's simple to assume that the ones with the most interactions are the most popular. These are the articles that we might suggest to new users (or anyone depending on what we know about them).

### III. User-User Based Collaborative Filtering
We may look at users who are similar in terms of the goods they have interacted with in order to develop better suggestions for IBM's platform users. These things could then be recommended to other users who have similar interests. This would be a step in the right direction for users to receive more personalised recommendations. This is the next thing I'll do.

### IV. Matrix Factorization
Finally, I will finish developing recommendations using a machine learning approach. I will create a matrix decomposition using the user-item interactions. I will see how effectively I can anticipate new articles an individual will engage with using Ir decomposition (spoiler alert: it's not great). Finally, I will talk about potential strategies I might utilise in the future and how I will test how effectively my recommendations are engaging consumers.


Source: [UDACITY - Nano Degree: Data Science](https://www.udacity.com/course/data-scientist-nanodegree--nd025?utm_source=gsem_brand&utm_medium=ads_r&utm_campaign=12908932988_c&utm_term=124509197431&utm_keyword=udacity%20data%20science_e&gclid=CjwKCAjwo8-SBhAlEiwAopc9W4IZK9m-po_p_F_5fg9RSzJ-snYSQkOFqqLf1lcEYE3ECs9UF0EvCBoCJYMQAvD_BwE)
