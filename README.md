# ML-Algorithms-
Implementation of Different ML Algorithms including: 1)Linear Regression 2)Support Vector Machine 3)Neural Networks 4) 
Decision Tree 5)k-NN 6) Naive Bayes 7)Logistic Regression

Linear Regression

It is used to estimate real values (cost of houses, number of calls, total sales etc.) based on continuous variable(s). 
Here, we establish relationship between independent and dependent variables by fitting a best line. 
This best fit line is known as regression line and represented by a linear equation Y= a *X + b.

The best way to understand linear regression is to relive this experience of childhood. 
Let us say, you ask a child in fifth grade to arrange people in his class by increasing order of weight, 
without asking them their weights! What do you think the child will do? He / she would likely look (visually analyze) 
at the height and build of people and arrange them using a combination of these visible parameters.
This is linear regression in real life! The child has actually figured out that height and build would be correlated to the
weight by a relationship, which looks like the equation above.

In this equation:

Y – Dependent Variable
a – Slope
X – Independent variable
b – Intercept
These coefficients a and b are derived based on minimizing the sum of squared difference of distance between data points 
and regression line.

Look at the below example. Here we have identified the best fit line having linear equation y=0.2811x+13.9. 
Now using this equation, we can find the weight, knowing the height of a person.

Linear_Regression

Linear Regression is of mainly two types: Simple Linear Regression and Multiple Linear Regression. 
Simple Linear Regression is characterized by one independent variable. And, Multiple Linear Regression(as the name suggests) 
is characterized by multiple (more than 1) independent variables. While finding best fit line, 
you can fit a polynomial or curvilinear regression. And these are known as polynomial or curvilinear regression.

SVM (Support Vector Machine)

It is a classification method. In this algorithm, we plot each data item as a point in n-dimensional space 
(where n is number of features you have) with the value of each feature being the value of a particular coordinate.

For example, if we only had two features like Height and Hair length of an individual, 
we’d first plot these two variables in two dimensional space where each point has two co-ordinates 
(these co-ordinates are known as Support Vectors)

SVM1

Now, we will find some line that splits the data between the two differently classified groups of data. 
This will be the line such that the distances from the closest point in each of the two groups will be farthest away.

SVM2

In the example shown above, the line which splits the data into two differently classified groups is the black line, 
since the two closest points are the farthest apart from the line. This line is our classifier. Then, depending on where 
the testing data lands on either side of the line, that’s what class we can classify the new data as.


Logistic Regression:

Don’t get confused by its name! It is a classification not a regression algorithm. It is used to estimate 
discrete values ( Binary values like 0/1, yes/no, true/false ) based on given set of independent variable(s). 
In simple words, it predicts the probability of occurrence of an event by fitting data to a logit function. Hence, it is also known as logit regression. Since, it predicts the probability, its output values lies between 0 and 1 (as expected).

Again, let us try and understand this through a simple example.

Let’s say your friend gives you a puzzle to solve. There are only 2 outcome scenarios – either you solve it or you don’t. 
Now imagine, that you are being given wide range of puzzles / quizzes in an attempt to understand which subjects 
you are good at. The outcome to this study would be something like this – if you are given a trignometry based tenth 
grade problem, you are 70% likely to solve it. On the other hand, if it is grade fifth history question, 
the probability of getting an answer is only 30%. This is what Logistic Regression provides you.

Naive Bayes

It is a classification technique based on Bayes’ theorem with an assumption of independence between predictors. 
In simple terms, a Naive Bayes classifier assumes that the presence of a particular feature in a class is unrelated to 
the presence of any other feature. For example, a fruit may be considered to be an apple if it is red, round,
and about 3 inches in diameter. Even if these features depend on each other or upon the existence of the other features,
a naive Bayes classifier would consider all of these properties to independently contribute to the probability that this
fruit is an apple.

Naive Bayesian model is easy to build and particularly useful for very large data sets. Along with simplicity, 
Naive Bayes is known to outperform even highly sophisticated classification methods.

Bayes theorem provides a way of calculating posterior probability P(c|x) from P(c), P(x) and P(x|c). 
Look at the equation below:
Bayes_rule

Here,

P(c|x) is the posterior probability of class (target) given predictor (attribute). 
P(c) is the prior probability of class. 
P(x|c) is the likelihood which is the probability of predictor given class. 
P(x) is the prior probability of predictor.

KNN (K- Nearest Neighbors):

It can be used for both classification and regression problems. However, it is more widely used in classification problems 
in the industry. K nearest neighbors is a simple algorithm that stores all available cases and classifies new cases by a 
majority vote of its k neighbors. The case being assigned to the class is most common amongst its K nearest neighbors 
measured by a distance function.

These distance functions can be Euclidean, Manhattan, Minkowski and Hamming distance. First three functions are used 
for continuous function and fourth one (Hamming) for categorical variables. If K = 1, then the case is simply assigned 
to the class of its nearest neighbor. At times, choosing K turns out to be a challenge while performing KNN modeling.







