# Case Study #3: Walmart - Confidence Interval and CLT

## Problem Statement

### Mindset

1. Evaluation will be kept lenient, so make sure you attempt this case study.
1. Read the question carefully and try to understand what exactly is being asked.
1. Brainstorm a little. If you’re getting an error, remember that Google is your best friend.
1. You can watch the lecture recordings or go through your lecture notes once again if you feel like you’re getting confused over some specific topics.
1. Discuss your problems with your peers. Make use of the Slack channel and WhatsApp group.
1. Only if you think that there’s a major issue, you can reach out to your Instructor via Slack or Email.
1. There is no right or wrong answer. We have to get used to dealing with uncertainty in business. This is exactly the skill we want to develop.

### About Walmart

Walmart is an American multinational retail corporation that operates a chain of supercenters, discount departmental stores, and grocery stores from the United States. Walmart has more than 100 million customers worldwide.

### Business Problem

The Management team at Walmart Inc. wants to analyze the customer purchase behavior (specifically, purchase amount) against the customer’s gender and the various other factors to help the business make better decisions. They want to understand if the spending habits differ between male and female customers: Do women spend more on Black Friday than men? (Assume 50 million customers are male and 50 million are female).

### Dataset

The company collected the transactional data of customers who purchased products from the Walmart Stores during Black Friday. The dataset has the following features:
Dataset link: [Walmart_data.csv][1]

- User_ID: User ID
- Product_ID: Product ID
- Gender: Sex of User
- Age: Age in bins
- Occupation: Occupation(Masked)
- City_Category: Category of the City (A,B,C)
- StayInCurrentCityYears: Number of years stay in current city
- Marital_Status: Marital Status
- ProductCategory: Product Category (Masked)
- Purchase: Purchase Amount

### What good looks like?

1. Import the dataset and do usual data analysis steps like checking the structure & characteristics of the dataset.
2. Detect Null values & Outliers (using boxplot, "describe" method by checking the difference between mean and median, isnull etc.)
3. Do some data exploration steps like:
   1. Tracking the amount spent per transaction of all the 50 million female customers, and all the 50 million male customers, calculate the average, and conclude the results.
   2. Inference after computing the average female and male expenses.
   3. Use the sample average to find out an interval within which the population average will lie. Using the sample of female customers you will calculate the interval within which the average spending of 50 million male and female customers may lie.
4. Use the Central limit theorem to compute the interval. Change the sample size to observe the distribution of the mean of the expenses by female and male customers.
   1. The interval that you calculated is called Confidence Interval. The width of the interval is mostly decided by the business: Typically 90%, 95%, or 99%. Play around with the width parameter and report the observations.
5. Conclude the results and check if the confidence intervals of average male and female spends are overlapping or not overlapping. How can Walmart leverage this conclusion to make changes or improvements?
6. Perform the same activity for Married vs Unmarried and Age
   1. For Age, you can try bins based on life stages: 0-17, 18-25, 26-35, 36-50, 51+ years.
7. Give recommendations and action items to Walmart.

### Evaluation Criteria

1. Defining Problem Statement and Analyzing basic metrics (10 Points)
   1. Observations on shape of data, data types of all the attributes, conversion of categorical attributes to 'category' (If required), statistical summary
   2. Non-Graphical Analysis: Value counts and unique attributes ​
   3. Visual Analysis - Univariate & Bivariate
      1. For continuous variable(s): Distplot, countplot, histogram for univariate analysis
      2. For categorical variable(s): Boxplot
      3. For correlation: Heatmaps, Pairplots
2. Missing Value & Outlier Detection (10 Points)
3. Business Insights based on Non- Graphical and Visual Analysis (10 Points)
   1. Comments on the range of attributes
   2. Comments on the distribution of the variables and relationship between them
   3. Comments for each univariate and bivariate plot
4. Answering questions (50 Points)
   1. Are women spending more money per transaction than men? Why or Why not? (10 Points)
   2. Confidence intervals and distribution of the mean of the expenses by female and male customers (10 Points)
   3. Are confidence intervals of average male and female spending overlapping? How can Walmart leverage this conclusion to make changes or improvements? (10 Points)
   4. Results when the same activity is performed for Married vs Unmarried (10 Points)
   5. Results when the same activity is performed for Age (10 Points)
5. Final Insights (10 Points) - Illustrate the insights based on exploration and CLT
   - Comments on the distribution of the variables and relationship between them
   - Comments for each univariate and bivariate plots
   - Comments on different variables when generalizing it for Population
6. Recommendations (10 Points)
   - Actionable items for business. No technical jargon. No complications. Simple action items that everyone can understand

### Submission Process

Type your insights and recommendations in the text editor.
Convert your jupyter notebook into PDF (Save as PDF using Chrome browser’s Print command), upload it in your Google Drive (set the permission to allow public access), and paste that link in the text editor.
Optionally, you may add images/graphs in the text editor by taking screenshots or saving matplotlib graphs using plt.savefig(...).
After submitting, you will not be allowed to edit your submission.

[1]: https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/293/original/walmart_data.csv?1641285094
