# Linear-and-Nonlinear-Gaussian-Naive-Bayes-Classifier-with-Visualization-on-A-Plane
Visualization of linear and nonlinear Gaussian Naive Bayes classifiers on a plane with matplotlib

## Bacic Idea
From an inspiration by [Naive Bayes demo](https://youtu.be/rqB0XWoMreU?t=2498) on lecture 10 of Kilian Weinberger's [Machine Learning for Intelligent Systems course](https://www.cs.cornell.edu/courses/cs4780/2018fa/) at Cornell University, I have built a conceptually same interactive linear and non-linear Gaussian Naive Bayes demo in Python with matplotlib event handling. <br />

## How it works
### Linear Gaussian Naive Bayes Classifier
When each of those decomposed one-dimension feature distributions, $P(x_{i} | y)$ follows Gaussian distribution and their variances are assumed to be the same across all labels (in this case when y=1 and y=-1), we can derive the closed form of a line that represents 50:50 case of falling into the two labels. In other words, Gaussian Naive Bayes classifier's decision boundary is linear in this case.

![linear_GNB](/images/linear_GNB.gif) <br />
<br />
<br />

### Non-linear Gaussian Naive Bayes Classifier
When the assumption about variances given label is violated, the decision boundary is not linear and there is no closed form of this.

![nonlinear_GNB](/images/nonlinear_GNB.gif) <br />

## Mathematical Background
### Naive Bayes Assumption

### linear Naive Bayes Assumption

## Setup

### git clone
git clone to have this repository on your local machine as follows.
```ruby
git clone git@github.com:YANJINI/Linear-and-Nonlinear-Gaussian-Naive-Bayes-Classifier-with-Visualization-on-A-Plane.git
```

### path control
To import modules written in this repository on your local macine, you need control path to this clone, which could be done as below.
```ruby
import sys
sys.path.extend(['/path_to_this_git_clone/Linear-and-Nonlinear-Gaussian-Naive-Bayes-Classifier-with-Visualization-on-A-Plane'])
```

### import 
Import these two classifiers in another py project as below.
```ruby
from GaussianNaiveBayes import twoD_coordinates_GNB
```

### Others
Check examples.py to see how to use the programes
