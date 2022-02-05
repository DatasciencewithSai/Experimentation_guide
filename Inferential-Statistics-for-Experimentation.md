
**Statistical Tests for Significance Test and Learn**


Details:

1.	Various Tests are used for test and learn statistical significance calculations
2.	Z test for Proportions
3.	T test for means
4.	Implemented in excel using formulas or in R
6.	Chi square test

Application:

1.	Applied to all AB tests and test and learn significance calculations

Chi square test: Z Test (or Chi-Square Test) (Pooled and Unpooled)

Application:

Measure statistical significance of metrics like Proportions example CVR, Bounce Rate


T Test:

Application:

Measure statistical significance for metrics like sales and IGM basically any continuous numerical metrics

•	It is a parametric test

Test used: Two Sample T test with equal variances

Assumptions:

Data is normally distributed

How to check normality of the data:

1.	QQ plot
2.	Distribution bell curve

Annova:

To measure the statistical significance of metrics like Sales and IGM when we have more than two groups (Multivariate testing)

Assumptions:
Normality

Types of Errors:

Type 1 Error: Alpha(false positives)

We say that there is a difference between two groups even though there is not(meaning we reject the null hypothesis when we should)

Alpha = 0.05 (Statistical significance)

Type 2 Error: Beta(True Negatives)

We reject the alternate hypothesis when we should not (meaning we say there is no difference when there is actually a difference between test and control groups)

Beta = 0.8 (As larger as possible) this is Power

P Value:

P value is nothing but probability of occurring the results by chance meaning if P value is 0.05 it means there is only 5% chance these results could be due to random chance or 95% we are confident these results are not due to random chance of occurring.


Central Limit Theorem:

Random sample drawn(with replacement) from the population will be normally distributed with population mean and standard deviation

•	holds true if the population is normal or not
•	Holds true for binomial and continuous variables

Types of Data:

1.	Categorical Data (Brown, blue, red) or state names
2.	Other data are best expressed in terms of ranks—that is, on ordinal scales.
3.	For example, yes/no, male/female, heads/tails, right/wrong. Such populations are referred to as dichotomous, or two-category, populations

When comparing the attributes of objects, events, or people, we are often unable to specify precise quantitative differences.

Parametric Tests:

T test
ANOVA
Z test

Parametric tests always involve two assumptions

1.	One is that the populations for the dependent variable are normally distributed. That is, the distribution of scores conforms to a bell-shaped distribution rather some other shape of distribution
2.	The second assumption is termed homogeneity of variance. Homogeneity of variance is the assumption that the populations for the dependent variable have equal variances

nonparametric statistics

Chi-square Test
Wilcoxon Test
Mann-Whitney Test

For data measured on a nominal scale, an ordinal scale, an interval scale with a nonnormal distribution, or a ratio scale with a nonnormal distribution , the investigator should use nonparametric statistics for the analysis.

Standard Error:

The standard error of a sample equals the standard deviation of the sample divided by the square root of the sample size (SE ¼ SD/On)

A standard deviation says something about the variation around the mean of the actual sample, whereas the standard error gives information on the variation one could theoretically expect in the sample mean if the experiment was repeated with a different sample

estimated standard deviation of a statistic, most often the sample mean (then known as SEM); this is a hypothetical figure. For example, the sample mean is the usual estimator of a population mean. The standard error gives an indication of how likely it is for the same mean to be obtained if the experiment was repeated. The 95% confidence


Correlation:

Increase in laptop purchases increased mouse purchased this is a linear relationship between two variables can be calculated which ranges from -1 to 1 (Increased alcohol purchased increased cigarette purchase)

Causation:

Results are caused by action taken meaning increase in marketing spend we saw increase in site traffic (Increase in smoking increased chances of lung cancer)


Primacy Effect:

When a new feature is launched through A/B test some times its is possible that we might see negative impact to the business that might be primacy effect where existing customers reluctant to adopt to new changes.

Novelty Effect:

This is opposite to Primacy effect where when a new feature launched through A/B test we see immediate positive impact to business but as we continue the test we might not see the same results this might be due to new customers reacting to it and over time fades out.

So both Novelty and Primacy effects wont long lost so test as divrse group of customers as possible when launching new features.


References:
1.	https://sphweb.bumc.bu.edu/otlt/mph-modules/bs/bs704_probability/BS704_Probability12.html#:~:text=The%20central%20limit%20theorem%20states,will%20be%20approximately%20normally%20distributed.
2.	https://uca.edu/psychology/files/2013/08/Ch10-Experimental-Design_Statistical-Analysis-of-Data.pdf (Experimental Design: Statistical Analysis of Data )
3.	http://www.dl.edi-info.ir/An%20introduction%20to%20inferential%20statistics.pdf (Introduction to inferential statistics review and practical guide)
4.	https://ncss-wpengine.netdna-ssl.com/wp-content/themes/ncss/pdf/Procedures/PASS/Tests_for_Two_Proportions.pdf (Z test/Chi square test for proportion) (Glossary) (paper)
5.	https://hbr.org/2017/09/the-surprising-power-of-online-experiments (Article)
6.	https://medium.com/codex/cracking-a-b-testing-for-interview-87e368162fae (False Discovry Rate, Bonferroni Correction)
7.	https://mgimond.github.io/Stats-in-R/z_t_tests.html
8.	https://towardsdatascience.com/the-art-of-a-b-testing-5a10c9bb70a4
