# Associations-between-hypertension-and-demographic-factors-goup-assignment
This was a group assignment for my categorical data analysis university course. The goal was to find out the relationship between hypertension and various demographic features such as age, cholesterol levels, and BMI. 

My contributions to this assignment included forming our null and alternative hypotheses, creating logistic and loglinear regression models to gain insight on the relationships between the variables as well as to test our hypotheses.

We hypothesized that hypertension is dependent on the aforementioned factors.
To be more specific, we constructed two alternate hypotheses; the first being that there exists a relationship between hypertension and the demographic factors, with the null hypothesis naturally stating that having hypertension is independent of all the other variables.

Our second alternative hypothesis stated that there exists a conditional relationship between hypertension and the demographic variables.

To test our first alternative hypothesis, we conducted a likelihood ratio test (LRT), which resulted in us rejecting the first null hypothesis. For the second alternative hypothesis, we ran an ANOVA test between an independent log-linear model and a saturated model. The result of the ANOVA lead us to reject the second null hypothesis, meaning that there exists a conditional relationship between hypertension and the demographic factors (excluding obesity).

Because the association between hypertension and obesity is well-known and medically documented, the fact that there was no relationship between hypertension and obesity in our models lead us to believe that the relationship is not linear. This would violate the assumption of linearly related variables of both logistic and log-linear regression, which explains the discrepancy.


  


