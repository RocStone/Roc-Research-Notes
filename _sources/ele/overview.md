# Overview
A good book to learn statistic.
I will write the main idea of this book in the future.

# Outline of the book and what I should pay attention to
1. Introduction **fast get main idea**
2. Overview of Supervised Learning **fast get main idea**
3. Linear Methods for Regression **familar**
4. Linear Methods for Classification **familar**
5. Basis Expansions and Regularization **what is expansion?**
1. Kernel Smoothing Methods **I know kernel, but what's smoothing?**
2. Model Assessment and Selection **Assessment means evaluation? I think it's all about different performance measure**
3. Model Inference and Averaging **what's model avearging?**
4. Additive Models, Trees, and Related Methods
5.  Boosting and Additive Trees **I forgot the main idea of boosting and what's additive trees?**
6.  Neural Networks **very familar**
7.  Support Vector Machines and Flexible Discriminants **familary with SVM but what's flexible discriminats?**
1.  Prototype Methods and Nearest-Neighbors **know a little with prototype. Familary with KNN**
2.  Unsupervised Learning **should be re-read carefully becase the main task of unsuperved learning is designing a good loss function**
3.  Random Forests **random feature selection + decision tree**
4.  Ensemble Learning **exploiting multiply models**
5.  Undirected Graphical Models **know very little, maybe markov decision process?**
6.  High-Dimensional Problems **interesting!**


# Detailed Outline
1. Introduction 1 **fast pass**
2. Overview of Supervised Learning 9 **get the main idea**
   1. 2.1 Introduction ......................... 9 **same as above**
   2. 2.2 Variable Types and Terminology.............. 9 **what variable?**
   3. 2.3 Two Simple Approaches to Prediction: Least Squares and Nearest Neighbors . . . . . . . . . . . 11 **A line has the lest sum of square of distance to misclassified data?Predicted according to the nearest neighbors.**
      1. 2.3.1 Linear Models and Least Squares . . . . . . . . 11 
      2. 2.3.2 Nearest-Neighbor Methods ............ 14
      3. 2.3.3 From Least Squares to Nearest Neighbors . . . . 16 **How?**
   4. 2.4 Statistical Decision Theory ................. 18 **like navie bayes?**
   5. 2.5 Local Methods in High Dimensions. . . . . . . . . . . . . 22 **what's the meaning of local here?**
   6. 2.6 Statistical Models, Supervised Learning and Function Approximation ................ 28 
      1. 2.6.1 A Statistical Model for the Joint Distribution Pr(X, Y ) ....... 28 **what you gonna do with joint distribution?**
      2. 2.6.2 Supervised Learning......... ....... 29
      3. 2.6.3 Function Approximation . . . . . . ....... 29 **what function to be approximated?**
   7. 2.7 Structured Regression Models ............... 32 **what's structed mean?**
      1. 2.7.1 Difficulty of the Problem ............. 32 **what difficulty?**
   8. 2.8 Classes of Restricted Estimators . . . . . . . . . . . **never know about resticted estimators**
      1. 2.8.1 Roughness Penalty and Bayesian Methods **!**
      2. 2.8.2 Kernel Methods and Local Regression . . .**local regression?**
      3. 2.8.3 Basis Functions and Dictionary Methods . **dictionary methods?**
   9. 2.9 Model Selection and the Bias–Variance Trade off . . 
3.  Linear Methods for Regression 43
    1.  3.1 Introduction ......................... 43
    2.  3.2 Linear Regression Models and Least Squares . . . . . . . 44 
        1.  3.2.1 Example:ProstateCancer ............ 49
        2.  3.2.2 The Gauss–Markov Theorem........... 51 **important!**
        3.  3.2.3 Multiple Regression from Simple Univariate Regression . . . . . . . . 52 **never know**
        4.  3.2.4 MultipleOutputs ................. 56 **NK**
    3.  3.3 SubsetSelection ....................... 57
        1.  3.3.1 Best-Subset Selection ............... 57 **NK**
        2.  3.3.2 Forward- and Backward-Stepwise Selection . 
        3.  3.3.3 Forward-Stagewise Regression . . . . . . . .
        4.  3.3.4 Prostate Cancer Data Example (Continued)
    4.  3.4 Shrinkage Methods.................... **never know**
        1.  3.4.1 RidgeRegression ................. 61 **L2**
        2.  3.4.2 TheLasso ..................... 68 **L1**
        3.  3.4.3 Discussion: Subset Selection, Ridge Regression and the Lasso ................... 69 **subset of what?**
        4.  3.4.4 Least Angle Regression .............. 73 **NK**
    5.  3.5 Methods Using Derived Input Directions . . . . . . . . . 79 **NK**
        1.  3.5.1 Principal Components Regression . . . . . . . . 79 **Something with egenvector i think**
        2.  3.5.2 Partial Least Squares ............... 80 **partial? what's another part?**
    6.  3.6 Discussion: A Comparison of the Selection and Shrinkage Methods ................... 82 ****
    7.  3.7 Multiple Outcome Shrinkage and Selection . . . . . . . . 84
    8.  3.8 More
        1.  the Lasso and Related Path Algorithms . . . . . 86
        2.  Incremental Forward Stagewise Regression . . . 86
        3.  Piecewise-Linear Path Algorithms . . . . . . . . 89
        4.  The Dantzig Selector ............... 89
        5.  The Grouped Lasso ................ 90
        6.  Further Properties of the Lasso. . . . . . . . . . 91
        7.  Pathwise Coordinate Optimization . . . . . . . . 92
    9.  3.9 Computational Considerations ............... 93
