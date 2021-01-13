# Introduction
Applying logistic regression without using existing libraries on a small dataset with limited
number of features (or entries) to predict which binary class each sample belongs to

# Objective:
We want to predict label “y”, from different combinations of the 14 features provided. we need
to select 3 different combinations of at least 5 features and we will be calculating the results for
these 3 combinations you have selected. For example: 1st combination: (x1, x3, x5, x7, x8), 2nd
combination: (x1, x2, x3, x4, x5, x6), and 3rd combination: (x1, x2, x3, x4, x5, x6, x7, x8, x9, x10,
x11, x12, x13) (i.e., all features) we will Try & see if you can find a specific combination that works well!

# Outcome

Plot cross-entropy, J(q) as defined {𝐽(𝜃) = −1/𝑚 sum[i = 1:m][𝑦^i log ℎ(𝑥)+ (1 − 𝑦^i) log (1 − ℎ(𝑥^i))]}
against the iteration count, for training and early stopping sets on the same plot. Display each fold
as a separate trace which means you will get 5 traces each for training and early stopping.
You will have to plot this for each of the 3 models separately. This means your script should output
3 graphs with 10 traces (crossentropy vs. iteration) displayed in each of them (5 for training and
5 for early stopping).

Plot the classification accuracy (not cross-entropy) against the iteration count for each
fold as a separate trace which means you will get 5 traces for each of the 3 models. Like
part (a) above, you will have to plot this for each of the 3 models separately. This means
your script should output 3 graphs with 5 traces (accuracy vs. iteration) displayed in each
of them.

the script will generate a total of 6 graphs (as described above) when run.
