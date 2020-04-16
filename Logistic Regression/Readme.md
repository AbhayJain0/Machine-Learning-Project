##   What is Logistic Regression?

Logistic regression is a traditional and classic statistical model, which has been widely used in the academy and industry. Unlike linear regression, which is used to make a prediction on the numeric response, logistic regression is used to solve a classification problem. For example, when a person applies a loan from a bank, bank is interested in whether this applicant will default in the future? (default or not default)

One solution is to make a prediction on the applicant future status directly, such as Perceptron, which is foundation to SVM and Neural Network.

The other solution, such as logistic regression, is to make a prediction on the probability that applicant will default. Due to the nature of probability, the prediction will fall in [0, 1]. By the rule of thumb, if the predicted probability is greater or equal to 0.5, then we can label this applicant as ‘default’; if the predicted probability is smaller to 0.5, then we can label this applicant as ‘not default’. However, the range of linear regression is from negative infinite to positive infinite, not in [0, 1]. Then sigmoid function is introduced to solve this problem. The expression of sigmoid function is:

![alt text](https://miro.medium.com/max/303/1*-XcDnVV0LLpV5XyZ2fqcig.gif)

The sigmoid function gives an S-shaped curve and saturates when its argument is very positive or very negative. 

The figure of sigmoid function:
![alt text](https://miro.medium.com/max/1400/1*UnSW1b5LdpFlBx5hR54J0w.png)
