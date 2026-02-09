# Case Study #2: Aerofit - Descriptive Statistics & Probability

## Question

Q1. Business Case: Aerofit - Descriptive Statistics & Probability

## Acceptance Criteria

### Mindset

1. Evaluation will be kept lenient, so make sure you attempt this case study.
1. Read the question carefully and try to understand what exactly is being asked.
1. Brainstorm a little. If you're getting an error, remember that Google is your best friend.
1. You can watch the lecture recordings or go through your lecture notes once again if you feel like you're getting confused over some specific topics.
1. Discuss your problems with your peers. Make use of the Slack channel and WhatsApp group.
1. Only if you think that there's a major issue, you can reach out to your Instructor via Slack or Email.
1. There is no right or wrong answer. We have to get used to dealing with uncertainty in business. This is exactly the skill we want to develop.

### About Aerofit

Aerofit is a leading brand in the field of fitness equipment. Aerofit provides a product range including machines such as treadmills, exercise bikes, gym equipment, and fitness accessories to cater to the needs of all categories of people.

### Business Problem

The market research team at AeroFit wants to identify the characteristics of the target audience for each type of treadmill offered by the company, to provide a better recommendation of the treadmills to the new customers.
The team decides to investigate whether there are differences across the product with respect to customer characteristics.

1. Perform descriptive analytics **to create a customer profile** for each AeroFit treadmill product by developing appropriate tables and charts.
1. For each AeroFit treadmill product, construct **two-way contingency tables** and compute all **conditional and marginal probabilities** along with their insights/impact on the business.

### Dataset

The company collected the data on individuals who purchased a treadmill from the AeroFit stores during the prior three months.

Dataset link: [Aerofit_treadmill.csv][1]

The dataset has the following features:

1. `Product Purchased`: KP281, KP481, or KP781
1. `Age`: In years
1. `Gender`: Male/Female
1. `Education`: In years
1. `MaritalStatus`: Single or partnered
1. `Usage`: The average number of times the customer plans to use the treadmill each week.
1. `Income`: Annual income (in $)
1. `Fitness`: Self-rated fitness on a 1-to-5 scale, where 1 is the poor shape and 5 is the excellent shape.
1. `Miles`: The average number of miles the customer expects to walk/run each week

#### Product Portfolio

- The KP281 is an entry-level treadmill that sells for $1,500.
- The KP481 is for mid-level runners that sell for $1,750.
- The KP781 treadmill is having advanced features that sell for $2,500.

#### What good looks like?

1. Import the dataset and do usual data analysis steps like checking the structure & characteristics of the dataset
1. Detect Outliers (using boxplot, “describe” method by checking the difference between mean and median)
1. Check if features like marital status, age have any effect on the product purchased (using countplot, histplots, boxplots etc)
1. Representing the marginal probability like - 
    what percent of customers have purchased KP281, KP481, or KP781 in a table _(can use pandas.crosstab here)_
1. Check correlation among different factors using heat maps or pair plots.
1. With all the above steps you can answer questions like: 
    What is the probability of a male customer buying a KP781 treadmill?
1. **Customer Profiling** - Categorization of users.
1. **Probability** - marginal, conditional probability.
1. Some recommendations and actionable insights, based on the inferences.

Later on, we will see more ways to do “customer segmentation”, but this case study in itself is relevant in some real-world scenarios.

### Evaluation Criteria

1. Defining Problem Statement and Analysing basic metrics **(10 Points)**
   1. Observations on shape of data, data types of all the attributes, conversion of categorical attributes to 'category' (If required), statistical summary
1. Non-Graphical Analysis: Value counts and unique attributes ​​**(10 Points)**
1. Visual Analysis - Univariate & Bivariate **(30 Points)**
   1. For continuous variable(s): Distplot, countplot, histogram for univariate analysis **(10 Points)**
   1. For categorical variable(s): Boxplot **(10 Points)**
   1. For correlation: Heatmaps, Pairplots **(10 Points)**
1. Missing Value & Outlier Detection **(10 Points)**
1. Business Insights based on Non-Graphical and Visual Analysis **(10 Points)**
   1. Comments on the range of attributes
   1. Comments on the distribution of the variables and relationship between them
   1. Comments for each univariate and bivariate plot
1. Recommendations **(10 Points)** - Actionable items for business. No technical jargon. No complications. Simple action items that everyone can understand

### Submission Process

- Type your insights and recommendations in the text editor.
- Convert your jupyter notebook into PDF (Save as PDF using Chrome browser's Print command), upload it in your Google Drive (set the permission to allow public access), and paste that link in the text editor.
- Optionally, you may add images/graphs in the text editor by taking screenshots or saving matplotlib graphs using plt.savefig(...).
- After submitting, you will not be allowed to edit your submission.

[1]: https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/125/original/aerofit_treadmill.csv?1639992749
