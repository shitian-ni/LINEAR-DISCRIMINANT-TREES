# LINEAR-DISCRIMINANT-TREES

The linear discriminant tree implemented here shows higher accuracy than sklearn's default decision trees.

In the inner optimization problem, scikit-learn's LDA finds a good split for the given two distinct groups of classes.  
In the outer optimization problem, exchange method (Yıldız and Alpaydın, 2005) is used to divide K classes into two groups.