![film production](https://github.com/user-attachments/assets/c701bc63-e9e1-4729-8087-095f5a1da7d5)

# FILM SUCCESS ANALYSIS

## INTRODUCTION

This project focuses on conducting exploratory data analysis (EDA) to provide actionable insights that will help a newly established movie studio create the most profitable films. By analyzing various datasets, we aim to uncover trends in genre performance, budget efficiency, casting success, and release timing. Our goal is to offer concrete business recommendations to guide the studio's decisions on film production, resource allocation, and release strategies.

### Market Challenge: Strategic Film Production Decisions

The new movie studio faces the challenge of making strategic film production decisions to successfully enter a competitive market. 

With established companies already creating original content, the studio must identify the most profitable film types to achieve commercial success while addressing additional business challenges.

### Minimizing Risks

To mitigate losses, the studio must analyze key factors influencing financial outcomes:

Identify loss-prone movie production aspects.

Evaluate genre, budget, and casting impacts on success or failure

Additionally, with many large players already dominating the industry, the studio needs to differentiate itself by developing unique strategies that will enable them to stand out in a crowded market.

### The Goal

The goal is to provide three concrete, actionable insights for the studio to maximize its box office revenue while minimizing financial risks and gaining a competitive edge. These insights should guide decisions regarding movie genre, budget allocation, cast selection, and strategic release timing.

## Key questions to Answer
1. How do ratings impact a movie’s success, and what ratings range is most common for successful films?
metric success for
2. What genres are consistently high-performing in terms of audience reception and revenue?
3. How does the release date (e.g., season or month) influence a movie’s box office performance?
4. What budget ranges are associated with profitable movies, and how does budget relate to revenue?
5. What factors contribute to higher revenues, and how can these be optimized for future productions?

## Data Understanding

The data for this analysis comes from multiple movie industry sources, including Box Office Mojo, IMDB, Rotten Tomatoes, The Movie DB, and The Numbers. 

These datasets provide rich insights into various aspects of movie performance such as 

![image](https://github.com/user-attachments/assets/e3be96b5-bada-43b6-8962-81eafd0de62c)

Steps taken in Data Preparation 

## Data Cleaning 

![image](https://github.com/user-attachments/assets/7a019866-3380-4f36-96b0-cf0ed4cb7e77)

Identifying High-Performing Movie Genres

What is the relationship between movie genres and their box office performance?

Which genres should the studio focus on producing?

The following charts demonstrates that relationship

## UNIVARIATE ANALYSIS

Drama is the genre that is most produced

![image](https://github.com/user-attachments/assets/eecd3c1e-2441-4755-a4d1-5379b923d2dc)

## BIVARIATE ANALYSIS

The genres 

Sci-Fi , Adventure  and Action  have the highest average Revenue 


![image](https://github.com/user-attachments/assets/333cedaa-32b8-46bb-89b9-490702768639)

## Predict Revenue Based on Movie Features

We need to predict box office revenue based on factors such as production budget, genre, runtime, release date, and ratings

This will help the studio forecast potential earnings for new projects

The following charts demonstrates that relationship

### Model coefficients

The model explains 92.21% of the variability of the data

![image](https://github.com/user-attachments/assets/c57c64bf-3b33-49d9-82a3-3bf575e35105)

Even after transformation, the model fails the Normality and Homoscedastic test as shown below, indicating the need to go for non- linear models.

![image](https://github.com/user-attachments/assets/7fe37f3a-4571-413f-b402-722e14e2656b)

## Evaluating Budget vs. Revenue Correlation

We need to determine the optimal budget range for producing profitable films

The following chart clearly shows that

There is a positive correlation of 0.748306 between production budget and World-wide gross (Revenue).

![image](https://github.com/user-attachments/assets/63fc5040-72cb-441a-9c21-b1bd5a60441b)

Higher budget movies tend to have a higher chance of being profitable, but profitability could be more concentrated in the lower budget ranges due to smaller production costs.

![image](https://github.com/user-attachments/assets/0321f5b7-14af-49f4-b924-eadc7b66d8b4)

## Seasonal Trends in Box Office Revenue

We explore the release dates and revenue data to identify seasonal trends in box office performance

The studio needs to schedule releases strategically.

The following chart clearly shows that

### Average Return On Investment(ROI)  over a period Of Months

The strong ROI in July for the Mystery genre implies that the audience may have a heightened interest in this genre during this time.

The business could consider aligning movie releases from the Mystery genre to this month to take advantage of the higher return potential.

![image](https://github.com/user-attachments/assets/f937d95a-86d1-476d-ae97-61d619ed57b6)

## Impact of Movie Cast and Crew on the Success of movie

What is the influence of cast and crew (e.g., directors, lead actors) on a movie's success ? 

The studio needs to use this as guide hiring decisions for future productions.

The following chart clearly demonstrates  that

The bar chart highlights that Director David Fincher consistently achieves the highest average ratings among directors who specialize in the genres of Horror, Thriller, or Mystery

 This suggests his exceptional skill in crafting compelling narratives within these genres, making him a standout among his peers.


![image](https://github.com/user-attachments/assets/5070a4e5-2f43-4a9b-81d8-8e9198b29993)

Catherine Keener, Lili Taylor, Ben Affleck, John C. Reilly, Tom Hanks, Harrison Ford, and Ewan McGregor are shown as the leading actors and actresses in Horror, Thriller, and Mystery genres with ratings above 7.5 and substantial audience engagement (over 9000 votes). 

Their repeated appearances across these genres demonstrate their strong on-screen presence, versatility, and appeal to both critics and large audiences.

![image](https://github.com/user-attachments/assets/0e9a5618-8f00-4bdd-a47b-fafd6e280f8c)

# Recommendations

Based on the analyzed data presented here are some recommendations

Focus on High-Performing Genres: Analyze historical data to identify which film genres consistently perform well at the box office. Prioritize producing films in these genres to maximize revenue potential.

Optimize Budget Allocation: Examine the relationship between production budgets and box office success. Allocate resources efficiently by investing in areas that have the highest return on investment, such as special effects for action films or renowned writers for dramas.

Strategic Release Timing: Study the timing of successful film releases to determine optimal release windows. Consider factors such as holidays, school vacations, and competitor release schedules to choose the best times for launching new films.

Leverage Star Power: Analyze data on the impact of star actors and directors on film success. Investing in popular or critically acclaimed talent can boost a movie's appeal and draw larger audiences. Collaborating with established names in the industry can also enhance the studio's reputation and attract attention to new projects.

# CONCLUSION

Through our exploratory data analysis, we've identified key strategies for the newly established movie studio to maximize box office revenue.
 
Our analysis has revealed that focusing on high-performing genres, optimizing budget allocation, strategically timing releases, and leveraging star power are crucial for success.
 
By implementing these insights, the studio will be well-equipped to make informed decisions, ensuring profitability and a strong presence in the competitive film industry.
![Filmska-preduzeca-1](https://github.com/user-attachments/assets/0d580aad-377e-4e23-9d57-2792b54bca22)














