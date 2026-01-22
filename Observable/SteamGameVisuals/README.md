# Steam Games Market Analysis

## Dataset
These visuals use publicly available data on games released on Steam, including information on genres, publishers, Metacritic score and user scores.

[Steam_Dataset.xlsx](https://github.com/user-attachments/files/24807375/Steam_Dataset.xlsx)

## Analysis Focus
I was interested in exploring how review scores vary across different game categories and genres on Steam, and how closely user ratings align with critic scores.

## Main insights

### Critics vs. User Scores
This scatterplot compares Metacritic critic scores with user scores across Steam games.

Many games show fairly close agreement between critic and user ratings, though there is some spread where player scores diverge from professional reviews. This highlights that player reception does not always align perfectly with critic opinion, without any single dominant pattern standing out across the dataset.

<img width="669" height="748" alt="criticVsUserScores" src="https://github.com/user-attachments/assets/411f2a3c-bafb-4ee3-b898-61b757becd83" />

## Additional exploration

### Market Distribution by Category
This treemap shows how games are distributed across major Steam categories, with area representing the number of titles and color indicating average Metacritic score.

The visualization provides a high-level view of which categories dominate the Steam marketplace, while also giving a rough sense of how review scores vary across categories. It was useful for identifying both popular categories and smaller niches that tend to be associated with stronger reviews.

<img width="1166" height="822" alt="categoryMarketDist" src="https://github.com/user-attachments/assets/2465153c-ab39-4d99-90ae-492462c2c645" />

### Genre - Publisher Relationships
This Sankey diagram explores how games flow from genres to publishers.

It was used as an exploratory view to understand how concentrated or diversified publishers are across genres, and to highlight potential patterns that could be examined more closely using more targeted visualizations.

<img width="1019" height="755" alt="sankeyGenreToPubFlow" src="https://github.com/user-attachments/assets/49783656-d0c7-4a35-8705-f3dae1f38b04" />
