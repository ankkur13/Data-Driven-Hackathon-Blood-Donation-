# Data-Driven-Hackathon-Blood-Donation-

Goal is to predict the last column, whether he/she donated blood in March 2007. You are provided the following set of information about the dataset:

* Months since Last Donation: this is the number of monthis since this donor's most recent donation.
* Number of Donations: this is the total number of donations that the donor has made.
* Total Volume Donated: this is the total amound of blood that the donor has donated in cubuc centimeters.
* Months since First Donation: this is the number of months since the donor's first donation.

### Evaluation Metric

Log loss =−1n∑ni=1[yilog(y^i)+(1−yi)log(1−y^i)]

The metric used for this competition is logarithmic loss. y^ is the probability that y=1. Logarithmic loss provides a steep penalty for predictions that are both confident and wrong. The goal is to minimize the log loss.

This dataset is very small, simple and clean. On 05/31/2018 I was under top 3% of the leaderboard. I used Logistic Regression and Random Forest for this small dataset.

----

Link for DataSet : https://www.drivendata.org/competitions/2/warm-up-predict-blood-donations/data/
