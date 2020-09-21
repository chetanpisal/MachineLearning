Regularization is to modify model line when we have additional data.
It is mathematical process which will descentize your model line.

## Advantage of Regularization

Reduce Model Complexity
Reduce computational Cost



L1 Regularizations - **Lasso Regression**
L2 Regularizations - **Ridge Regression**

We apply regularization when our model is **overfit**.
regularization can be achieved through regression.


**Ridge Regression**

Ridge Regression = Loss + Penalty. (With Sqauree of **W** Value)

Increasing value of constant (alfa)we can reduce magniture of co-efficient 

*Magniture of co-efficient is almost Zero*

**Lasso Regression**


Ridge Regression = Loss + Penalty. (With absolute of **W** Value)

Increasing value of constant (alfa)we can reduce magniture of co-efficient

*Magniture of co-efficient will be equal to Zero*

It works like **Feature Selection**



### Elastic Net Regression


when independent variables(Features) are hightly co-related with each other



_Elastic Net Regression_ = Loss + Penalty of Ridge Regression + Penalty of Lasso Regression
