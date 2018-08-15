# Multiple Linear Regression
The main difference between MLR and SLR is in the number of predictors. In the case of SLR, the equation is in the form
$$\hat{y} = b_0 + b_1x $$


MLR differs as it uses multiple predictors in it's equation.
$$\hat{y} = b_0 + b_1x_1 + \dots + b_px_p$$
The best way to view the data is by use of a $\bf {scatter}$ $\bf{ plot}$ $\bf{matrix}$ that shows the relationship between the predictors.
It is important to note that the term linear in MLR refers to the $b$ i.e the equation is linear in the $b$-parameter.
It is also possible to encounter models with $\bf{interactions}$. Interactions in a model simply means that the effects of one variable on the response variable when it interacts with another.
### Example
Consider a case where a researcher wants to study factors affecting the performance of a student in school. The researcher may be interested in determine if longer learning hours improve performance and if children from higher economic background perform better. This two factors are referred to as the main effects of the experiment. In this case interaction here the child understudy puts long hours on study and also comes from a wealthy background. This two factors may favor or disfavor the child.
#### ***How to determine interactions
The equation below shows a model that has interaction

$$ \hat{y} =b_0 + b_1x_1+b_2x_2 +b_{12}x_1x_2$$
It is important to distinguish between interaction and confonding. In confounding, the effects of one variable are not distingishable from the effects of anot
<!--stackedit_data:
eyJoaXN0b3J5IjpbNzc1OTE5ODUzLC0xMzA5MjgyMzgyLDExMz
QzOTI5MiwxNzY2OTU5MTAsLTUxNjMzMDEyMV19
-->