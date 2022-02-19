# Experimentation_Guide

**Objective:**
This is the complete guide for controlled and uncontrolled experimentation. It includes resources required for experimentation.
Purpose of the document is to put together all resources and information related to Randomized Controlled Experiments(A/B tests) and Quasi Experiments/ Natural Experiments (When Randomization is not possible). This should serve as guide for experimentation and will evolve over the time with resources. Topics should cover all the way from technical to business questions related to experimentation. Includes all the information I have gathered over the years. It covers Statistical concepts behind experiments and technical tools for execution and implementation. Resources from industry experts and research in the field of experimentation.

**Table of Contents:**

1.	Steps involved in Digital experimentation
2.	Statistical Concepts
3.	Tools
4.	Metrics
5.	Books
6.	Experts/Leaders
7.	References
8.	Industry leading Companies

**Types of Experimentation:**
1. Randomized Controlled Experiments(A/B tests)
2. Quasi Experiments/ Natural Experiments (When Randomization is not possible)

**Application of Randomized Controlled Experiments(A/B Tests)**

1. Website Development
  a. E-commerce Product development
  b. Feature launch
2. Digital Operations
  a. Webpage Content
  b. Onsite Promotions
  c. Content aesthetics, positioning

**Application of Quasi or Natural experiments**

1. Retail store level experiments
2. Marketing DMA level experiments
3. Customer level experiments

**Typical steps involved in experimentation**

1.	Pre-analysis and Planning
2.	Test Design and execution
3.	Test Analysis and Results

**Complete Guide to A/B Testing**

1. https://www.shopify.com/blog/the-complete-guide-to-ab-testing (Shopify)

**Companies who built their own experimentation Platform:**

These are leading companies that are leaders in online experimentation. They are using the experimentation platform for variety of purposes all the way from testing new product launches to small change to button on website.

1. Netflix -- https://research.netflix.com/research-area/experimentation-and-causal-inference
2. Airbnb -- https://medium.com/airbnb-engineering/https-medium-com-jonathan-parks-scaling-erf-23fd17c91166
3. Uber -- https://eng.uber.com/xp/
4. Microsoft -- https://exp-platform.com/
5. Linkedin -- https://engineering.linkedin.com/blog/topic/experimentation
6. Intuit -- https://www.intuit.com/blog/innovation/engineering/meet-wasabi-an-open-source-ab-testing-platform/
7. facebook -- https://ax.dev/
8. Groupon https://people.groupon.com/2018/groupon-data-driven-experiment-chicago/  
9. Etsy - https://codeascraft.com/2018/10/03/how-etsy-handles-peeking-in-a-b-testing/
10. Twitter - 4.	https://blog.twitter.com/engineering/en_us/a/2015/twitter-experimentation-technical-overview.html


**Experts and Leaders in Experimentation**

1. Ron Kohavi, PhD -- http://ai.stanford.edu/~ronnyk/
2. Stefan Thomke -- https://www.hbs.edu/faculty/Pages/profile.aspx?facId=6566
3. Ya Xu -- https://scholar.google.com/citations?user=YMA322YAAAAJ&hl=en

**A/B Testing Courses Online**

1. https://www.udacity.com/course/ab-testing--ud257

Data Science certification Courses
1. HarvardX's Data Science Professional Certificate (available on edX, Data Science using R)
2. IBM's IBM Data Science Professional Certificate (available on edX, Data Science using Python)
3. SQL for Data Analysis course by Udacity ( https://learndigital.withgoogle.com/digitalgarage/course/sql-for-data-analysis )

**Experimentation Books**

1. Trustworthy Online Controlled Experiments: A Practical Guide to A/B Testing:  https://www.amazon.com/Trustworthy-Online-Controlled-Experiments-Practical/dp/1108724264
2. Experimentation Works: The Surprising Power of Business Experiments By Stefan Thomke: https://www.amazon.com/Experimentation-Works-Surprising-Business-Experiments/dp/163369710X/ref=sr_1_1?keywords=experimentation+works&qid=1565294493&s=gateway&sr=8-1
3. A/B Testing by Dan Siroker
4. You should test that by Chris Goward
5. Mastering 'Metrics: The Path from Cause to Effect
6. How to Measure Anything by Doug Hubbard’s
7. Lean Analytics: Use Data to Build a Better Startup Faster
8. http://faculty.marshall.usc.edu/gareth-james/ISL/


**Leading A/B Testing Paid Platforms**

1. Adobe Target -- https://business.adobe.com/products/target/adobe-target.html
2. Optimizely -- https://www.optimizely.com/products/intelligence/web-experimentation/
3. Monetate -- https://kibocommerce.com/personalization-software/
4. Google Optimize -- https://support.google.com/optimize/answer/6197440?hl=en#zippy=%2Cin-this-article
5. Visual Website Optimizer(VWO) -- https://vwo.com/

**Tools:**

Tools for experimentation includes Data accessing tools, Data analysis tools, Data reporting tools, and statistical analysis tools.
Tools also includes experimentation execution Tools like Monetate and Optimizely for digital controlled experimentation. APT for offline store level experimentation.

Tools also includes web analytics tools that captures data and gives users great control on ease of using the data. These tools include IBM Coremetrics, Google Analytics, Adobe Analytics. Web user session viewing tools like Fullstory and Tealeau are also very useful.  

Data accessing, analysis and reporting tools:
SQL is primarily used for data accessing and minimal data analysis on the query window. Splunk can be used for real-time reporting and data collection. One should definitely have great understanding of data warehouses like Teradata or Snowflake or unstructured data warehouses.

* Data analysis tools range from SQL and excel and R and Tableau.
* Data reporting tools includes Excel, Tableau or Cognos.
* Statistical Analysis Tools includes primarily R, excel, Python.

**Metrics**

Defining the key metric for any test is very crucial and there are many key metrics that are involved in eCommerce experimentation.

**eComm website metrics**:

1.	CVR(Conversion Rate)
2.	Sales
3.	Order
4.	AOV (Average order value)
5.	RPS (Revenue per session)
6.	ATC Rate(Add to cart rate)
7.	Cart abandonment rate
8.	Checkout initiation rate
9.	Email submission rate
10.	Subscription rate
11.	CTR (Click through rate)
12.	Attach rate (Item attached with base sku)
13.	Impressions
14.	Clicks
15.	Sessions
16.	Customer life-time value
17.	Customer churn rate
18.	Email opens
19.	Email click through
20.	ROAS (Revenue on ad spent)
21.	ROI (Return on investment)
22.	IGM (Gross margin)

**Statistical Concepts**

Below are the list of statistical concepts and models used for Pre analysis, Test results measurement.

* Statistical Significance Tests
*	Continuous Metrics
*	Binary Metrics
*	Outlier Analysis
*	Power Analysis
*	Causal Impact
*	Forecasting
*	Predictive Analytics
*	Standard Error
*	Standard Deviation
*	Variance
*	Bias
*	Linear Regression Analysis
*	Log regression analysis
*	Central Limit theorem
*	Law of large numbers
*	Inferential statistics
*	Sensitivity
*	Specificity
*	Decision Tree method
*	Causal Inference
*	Time series analysis
*	Cluster Analysis
*	Bonferroni Correction
*	False Discovery Rate
*	Causality
*	Scaling Methods
*	Euclidean Distance calculation
*	Principal Component Analysis (PCA)
*	Propensity Score Analysis
*	Market Matching
*	Randomization Methods
*	Regression Discontinuity
*	Difference in Difference Regression  

**Statistical Significance Tests:**

1.	T test
2.	Z test
3.	Chi-square Test
4.	K Means Cluster
5.	Rosners outliers test
6.	Mann-Whitney Test

Statistical methods used to measure statistical validity of test results. For experimentation mainly inferential statistical methods are used to measure statistical significance. There are two kinds of approaches involved in measuring significance and test results they are

•	Frequentist Methods
•	Bayesian statistics methods

Under Frequentist Methods are based on normal distribution concepts and they include inferential statistical methods. Various statistical methods that are used in digital controlled experimentation are

**Statistical Significance:**

Statistical significance estimates the validity of the test results and is a measure of false positives and lesser the P values more confidence in the numbers.

There are various methods exists to measure significance in difference scenarios and various metrics.

Continuous Metrics:

In this category metrics like sales and IGM and any other metrics that are based on averages fall under this category.

Mean Tests:

1.	T-test

Median Test:

This is similar to T test for averages but used for median.
1.	Mann -Whitney Test (Hart, 2001)

Binary Metrics:

Metrics like Conversion rate and metrics related to proportions does fall under this category.

1.	Z-test for proportions
2.	Chi square test for categorical variables

**Outlier Analysis:**

Its very crucial for controlled experiments to exclude outliers from data and there are various methods available to identify outliers in data. Excluding outlier’s data also brings questions from business regarding impact of data excluded on incremental benefits from tests. It’s a balance between statistics and business when dealing with outliers.

1.	Quantile plot
2.	K-means cluster analysis
3.	Rosners Test for outliers [1]

**Power Analysis:**

Power analysis is used to estimate sample size required to execute test with minimal desired lift in the specified metric.

Sample Size Estimation for Continuous Metrics (Averages)
Sample Size Estimation for Binary metrics (CVR)


**Causal Impact: (R Package)**

Causal inferences methodologies are used to measure the causal impact from the intervention meaning we can use this to measure the impact of a particular offer or promotion. Causal Impact can be used measure the incremental benefits from running the campaign based on pre-post analysis (which is something different from regular controlled digital experiments which is always during the test comparison).  [3]


**Forecasting:**

I have used the Prophet R Package for forecasting traffic for based on spend for digital marketing. The package is very robust, and it can handle for lot of exceptional scenarios in forecasting. [4]

**Marketing Channel Attribution:**

I did used channel attribution package from R which is based on Marco chain model to give credit to each touchpoint in customer journey before making a purchase on the site. Mostly focused towards digital marketing. This package does lot in terms of simplifying the use of model application. And there are various kinds of attributions like last click, first click, linear, proportionate attribution. [5][6]

**Bias:**

There are various kinds of bias that need to be taken care of for valid experimentation results. [1]

•	Selection Bias
•	Randomization Bias
•	Statistical Bias

**Bonferroni correction:**

Significance required to eliminate error by correction method.
Divide the significance level 0.05 by the number of tests in the multiple testing. Say if you are measuring 20 tests, then your significance level for the test should be 0.05/20 = 0.0025. The problem of Bonferroni correction is it tends to be too conservative. If many metrics are tested at the same time, maybe none of them turned out to be significant.

**False Discovery Rate:**

Control false discovery rate (FDR): FDR = # false positives / # total rejections.

**Causality:**

Best scientific way to prove causality, i.e., the changes in metrics are caused by changes introduced in the treatment(s)[2]


Reference:
1.	https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3136079/ (Randomization Bias)  
2.	https://exp-platform.com/Documents/2015-08OnlineControlledExperimentsKDDKeynoteNR.pdf
