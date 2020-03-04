# Eluvio-DS-Challenge
Repository holding my solutions for the Eluvio DS Challenge

The solutions are present in the ELuvio_Challenge.ipynb file.

A pdf has also been attached along with it, which shows the output in pdf format.

**Problem Statement**

1) Looking for any patterns by visually observing data and doing some processing

2) Creating a simple model using as few features as possible (one feature), to negate the effects of a huge dataset. 

**My observation**

1) First, I thought I should check if all the posts belong to worldnews category. Turns out that they do. Also, all posts have 0 downvotes. Hence, both of these features are redundant and can be dropped when we need to create a model, as the dataset is already pretty large as mentioned.
Then, I checked if over 18 posts have more upvotes than other posts. It turned out while over 18 posts were pretty less, they received more upvotes per average than other posts.
Then I found out the top authors by upvotes and number of posts, and then also found out the top authors sorted by average number of upvotes per post. This would let me know which authors would get more upvotes than others.

2) As dataset is large, I tried to remove features and focus on one of the features, namely, the titles of the posts. This enabled me to create highly accurate models using SVM and Logistic Regression, which predicts whether a post will lie in the top 85 percentile of all the posts. Hence, I was successful in creating a highly accurate model using only one set of features. If we add some other features, we will probably get a little more accurate model.
