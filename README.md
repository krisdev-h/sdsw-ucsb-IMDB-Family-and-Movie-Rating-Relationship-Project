# sdsw-ucsb-movie-protagonist-project

## Abstract
Our IMDb Family and Movie Rating Relationship Group Project utilizes 8 classification models: K-Nearest Neighbors, Random Forest, Elastic Net, Pruned Decision Tree, Gradient-Boosted Tree, Linear Discriminant Analysis, and Native Bayes. These models predict 3 rating range classes: `Low`, `Medium`, and `High`. 

Utilizing `roc_auc` metrics, at the end of our modelling we
determine that the Linear Discriminant Analysis was our top performing model as it had the highest `roc_auc` metric of 0.771, which we fit to our testing set. 

Using a `rmse` or root mean square error metric for predicting whether movies are family related or not, we determine that the average difference between our predicted and actual values is around 9%. We finally generate interactive Shiny app visualizations for movie ratings, genre, and family relation. 

**Please Reference our HTML Final Report for more Details**
