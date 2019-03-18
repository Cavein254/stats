Logistic Regression
It differs from the normal linear regression as it does not try to predict the value  of a variable rather it determines the likelyhood(probability) of that input bbelonging to the a given class. LR uses $\bf{odd \, ratio}$ to calculate these probabilities. To calculate the odds of an event happening

$$odds = \frac{P(y=1|x}{1-P(y=1|x)}$$

Taking the natural logarithm in order to create a logistic equation,
$$Logit(P(x))=in(\frac{P(y=1|x}{(1-P(y=1|x)}). Since in LR the probability is assumed to be linear with respect to x, it therefore becomes

$$Logit(P(x))=a + bx$$
substituting to the equation it therefore becomes:

$$\frac{P(y=1|x}{(1-P(y=1|x)} = e ^{a + bx}$$

$$P(y=1|x) = \frac{e ^{a + bx}}{1 + e ^{a + bx}} = \frac{1}{{1 + e ^{-(a + bx)}}}$$


in cases where multiple **regressors** are needed such as;
$$Logit(P(x))= w_0x^0 + w_1x^1 + w_2x^2 + w_3x^3 ... + w_nx^n =w^Tx$$


$$\frac{1}{{1 + e ^{-(w^Tx)}}}$$
from [https://simple.wikipedia.org/wiki/Logistic_Regression]
[http://logisticregressionanalysis.com/376-understanding-logistic-regression-output-part1/]














