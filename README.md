# Recommendation of tariffs

We have data on the behavior of customers who have already switched to these tariffs (from the course project "Statistical Data Analysis"). You need to build a model for the classification task that will select the appropriate tariff. You don't need to preprocess the data - you've already done it.

Build the model with the largest *accuracy* value possible. To pass the project successfully, you need to get the proportion of correct answers to at least 0.75. Check *accuracy* on a test sample yourself.

## Data description

Each object in the dataset is information about the behavior of one user in a month. Known:
 - calls - number of calls,
 - minutes - total duration of calls in minutes,
 - messages - number of sms-messages,
 - mb_used - used Internet traffic in Mb,
 - is_ultra - what tariff was used during the month ("Ultra" - 1, "Smart" - 0).
