

**Propensity Score Analysis**


Details:

•	Is used to reduce the selection bias when you don’t have freedom of randomizing the data for test and Control Splits

•	Propensity Score Matching uses Logistic regression in the logic
•	Propensity Score matching considers multiple input variables for model building
•	This can be executes in R using "MatchIt" package
•	Matching of two samples is done using Nearest Neighbors Method but there other methods for exploration
•	Test and Control Groups are matched based similar propensity scores

Steps Involved Methodology

1.	The first step is to preprocess data sets, identify outliers, and interpolate missing values.
2.	In the second step, a model is specified, such as logistic regression, and trained on the dataset to predict whether a patient will be treated. For every patient, the trained model generates a probability of receiving treatment; i.e., his or her PS.
3.	The third step refers to matching based on PS, where different matching methods are tried, such as nearest neighbor, or optimal or genetic matching. In
4.	the fourth step, the balance of covariates between treatment and control groups is checked by calculating balance statistics and generating plots. A poor balance indicates that the model estimating PS needs to be respecified.
5.	In the fifth step, the treatment effects are estimated using matched data, and this is followed by the last step, where sensitivity analyses are performed to check the robustness of study results for hidden bias

 Application:
 * Can be used for store level testing

Example:

Data:

R code:

Results:


Reference:
1.	 https://www.redjournal.org/article/S0360-3016(20)30888-9/fulltext
2.	https://datascienceplus.com/how-to-use-r-for-matching-samples-propensity-score/
3.	https://atm.amegroups.com/article/view/61857/html  detailed explanation
