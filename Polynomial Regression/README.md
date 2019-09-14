* Used an example dataset, created using random values (decelerated growth) as well as, a csv showing salary prices of different level positions (accelerated growth)

* Underfitting is usually caused due to either:
    * A lack of data to build an accurate model or attempting to build a linear
    * Building a linear model on non-linear data
* In both cases of underfitting, the line is unable to accurately capture the patterns of the data.
* On the other hand, if the model has a high variance, i.e. the model is too complex and passes through most of the data points, it will overfit

* In the Example cases: 
    * Degree of 1 proved to underfit the data, having a high bias and a low variance
    * Degree of 3 / 4 proved to fit the data correctly, having a low bias / variance
    * Degree of 20 proved to overfit the data, having a low bias and a high variance
