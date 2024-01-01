WEEK 1 (Asgn1):

We constructed a Simple Linear Regression model being provided with a training dataset comprising of one feature (input column) and a
corresponding target (output column) to predict a target variable. We utilized the train dataset to train the model and predict the output of the given test dataset, which we then made into the 'predictions.csv' file. We further split our training dataset into train and test one so that we can calculate error for test dataset as well. Also plotted scatter plot of Feature v/s Target with actual and predicted values with a regression line for the predictions.

WEEK 2 (Asgn2):

After analyzing multiple runs with different parameter values for all the parameters each time,
I finally conclude that the Thompson sampling algorithm would be the most preferable algorithm of the 3, as we get the least total regret for this algorithm every time. 
In general, comparing algorithms based on their total regret can be a reasonable approach to evaluate their performance, especially in the context of multi-armed bandit problems. 
The total regret provides a measure of how well an algorithm is performing compared to an optimal strategy that always selects the best arm.
The algorithm with the least total regret is generally preferable, as it indicates that the algorithm is making better decisions and accumulating fewer regrets over time. 
So we can also conclude from the same logic that Epsilon Greedy is the least preferable one. We can also point out our observations just by looking at the plot!
