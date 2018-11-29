---
title: Insert title here
key: 83a1ced488978ee6fb5396bd1f5ebc04

---
## How Confident Are You?

```yaml
type: "TitleSlide"
key: "39293ca52c"
```

`@lower_third`

name: Evan Kramer
title: Instructor


`@script`
This lesson will teach you some simple ways to distinguish between two groups using confidence intervals and t-tests. By the end of this chapter, you should be able to define these terms and use formulas to calculate significant differences between groups.


---
## Explore the Data

```yaml
type: "FullImageSlide"
key: "cce701e15b"
```

`@part1`
![](https://assets.datacamp.com/production/repositories/4139/datasets/76e17596177fa4336c66312f6c9f672a5248a5c8/dc2.PNG)


`@script`
Imagine we have the following data set, which lists actual sales for each of the last 19 days. An analyst on our team also created two sets of predictions using a number of different assumptions (such as whether the economy was improving, if it was sunny outside, etc.). We compared each prediction to the actual value on that day, and we want to determine which set of predictions is more accurate, by comparing to our actual sales data.


---
## Confidence Intervals (CI)

```yaml
type: "FullSlide"
key: "b441ad0dc3"
```

`@part1`
- Ranges of values that contain the true parameter X% of the time {{1}}
    - Example: 95% CI contains the true value 95 of 100 data collections
- Function of three factors {{2}}
    - alpha (confidence level) {{3}}
    - variation in the data (standard deviation) {{4}}
    - number of data points {{5}}


`@script`
Confidence intervals, or CI for short, can help us do just that. They can assess the accuracy of our predictions by estimating the amount of error in the data. 

Confidence intervals are ranges of values that contain the true parameter a certain percentage of the time. When calculating CIs, we specify how much certainty we expect to have. For example, if we collect data 100 different times, a 95% confidence interval will contain the true value 95 of those times.

CIs vary based on three factors: 1) the alpha, or confidence level; 2) the variance of the data, as measured by its standard deviation; and 3) the number of observations the data set contains. 

The higher the confidence level, the larger the interval. This should make intuitive sense. A larger range (or interval), gives us more confidence that a given value will fall within it. A typical alpha level is 0.05 for 95% confidence. 

The variation also impacts the size of the confidence interval. Data with more variation requires a larger confidence interval, as we grow less certain that our sample represents all the variation in the true data. 

Finally, a higher number of observations decreases the size of the confidence interval because more data points give us greater predictive power and confidence.


---
## Know Your Bounds

```yaml
type: "TwoColumns"
key: "fe6093ce4e"
```

`@part1`
- Upper and lower bounds
-


`@part2`
![](https://assets.datacamp.com/production/repositories/4139/datasets/c07bd3e92cba2df4eeeadb0737c12a321c8bbd6b/dc3.PNG) {{2}}


`@script`
We typically refer to confidence intervals by their upper and lower bounds. Let's practice calculating these. Let's say we want to calculate the upper and lower bounds of a 95% confidence interval for the average sales over the last 19 days.


---
## Let's Practice!

```yaml
type: "FinalSlide"
key: "407a6a4d5a"
```

`@script`
Let's test your skills.

