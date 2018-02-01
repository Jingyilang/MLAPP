## 8.1 Introduction
一种建立概率分类器的方法是 to create a joint model of the form p(y,x) and then to condotion
 on x, thereby deriving p(y|x). 这就叫做生成模型。 一个替代方法是直接拟合这样的模型p(y}x), zhe 
 叫做判别模型， 这就是我们这一章讨论的。 特别的是，我们将假设这些判别模型参数是线性的。 我们将会
 看到拟合起来就很简单。 在8.6， 我们比较生成和判别模型，在后面的章节， 我们将会考虑非线性和无参数
 判别模型。
 
 ## 8.2 Model specification
 
 就像我们在1.4.6中讨论的 逻辑回归对应于下面的二分类模型：
 
 ## 8.3 Model fitting
 
 这章中，我们讨论估计逻辑回归模型参数的方法。
 
 ### 8.3.1 
 
 NLL在逻辑回归里是
NLL(W) = -\sum_
 这这叫做交叉熵误差模型。
 
