# Instagram Reach Analysis Case Study

This case study explores the factors that influence Instagram reach using data from the account of the founder of Statso. It examines the distribution of impressions from different sources, content analysis, the relationship between metrics, conversion rate, and modeling.

## Key Insights

- Home-based reach accounts for 45%, followed by hashtags (33.6%), explore (19.2%), and others.
- Content analysis highlights popular words in captions and hashtags.
- Likes and saves are strongly correlated with impressions, while comments and shares have a weaker impact.
- Conversion rate (followers/profile visits) is 5.3%.
- Profile visits and followers gained exhibit a linear relationship.

## Modeling

A PassiveAggressiveRegressor model is trained to predict Instagram reach based on likes, saves, comments, shares, profile visits, and followers. The model achieves an accuracy of 88% on the test set.

## Conclusion

Data-driven insights and modeling can help content creators optimize their Instagram strategy, focusing on engaging content, effective hashtag selection, and maximizing profile visits.
