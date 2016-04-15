# Data For Diplomas
This project won 3rd place in AT&T’s Data for Diplomas data science competition. Please refer to the competition website for information: datafordiplomas.devpost.com

Our final submission website is at: www.datafordiploma.com

# Competition Summary
The purpose of this competition was to predict high school graduation rates and identify actionable levers that policymakes can pull to increase graduation rates. Grading was done according to three different metrics:

1) Predictive power: how accurately can your model predict high school graduation rates?

2) Actionable insights: what are the most actionable insights from your analysis?

3) Data visualization: how can you display the information and results to a general audience?

# Results

Our analysis aims to predict high school graduation rates using ~140 variables, including economic security household stability, school spending, and weather variables. We built a random forest model which had an out-of-bag score for of 0.68, meaning that we were able to predict about 68% of the variation in the data with our model. Our simplified model captured 60% of the variation in the data.

We had several actionable insights from our model:
1) Colder regions tend to have lower graduation rates. Policy-makers and school officials should introduce mechanism or change school year cycles to mitigate the effect of adverse weather.

2) There are diminishing returns to school spending. In fact, our model predicted that increasing school spending would **not** have an effect on graduation rates, but decreasing school spending **would lower** graduation rates.

3) Household stability is a more important predictor of graduation rates than economic wellbeing. Beyond school programming, school officials and policy-makers should also offer services to help stabilize households and communities.

