LOGISTIC REGRESSION (CLASSIFICATION)
Works well with binary classification

dataset - study hours, play hrs, pass/fail
Fixed no of categories

Let's say, I assume a case where if I study more than 3 hrs, pass otherwise fail.

If we try to do this with liener regression with best fit line, let's say if op is less than 0.5 pass otherwise fail. Problem is - if I have outlier, the value for 5 hrs of study is also resulting in fail as per line of best fit, which is not right. 
(Outlier - I extend the x axis even further, the line of best fit will change because the plot of that value as per y axis will make it change)

So we need a way to ensure outliers don't mess up our result.

<img width="1886" height="720" alt="image" src="https://github.com/user-attachments/assets/3b3f9cd2-123b-4151-9e89-16c93aa41c37" />

So, this algo ensures your graph is non linear to ensure the outliers don't imact your classification.
