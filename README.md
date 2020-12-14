# Decision Trees Learning

In this coursework, I was given a dataset in diabetes.txt which contained the following information on a number of female patients:

1. Number of pregnancies
2. Plasma glucose concentration
3. Diastolic blood pressure
4. Fold thickness of tricep skin
5. Serum insulin
6. BMI
7. Diabetes pedigree function
8. Age
9. Whether they had diabetes or not

The task was to create a classifier for predicting whether a patient had diabetes. This coursework is contained in a Jupyter notebook and makes use of Pandas, Matplotlib, and SkLearn. The notebook begins with some simple functions showing the data, and separation of the input and target.

## Task 1

Task 1 asked for the mean, median, SD, and correlation matrix for the input attributes. It then asks for a chart demonstrating the data. Pandas provides simple functions for the first half of this task. The second half involved constructing a boxplot using matplotlib and seaborn.

## Task 2

Task 2 first asked to build a DT classifier and train it on a subsection of the diabetes.txt dataset, using the remainder as a testing set. The training was run 10 times with different splits, and the accuracy, sensitivity, and precision were recorded. The mean of each score was also calculated. Next, an investigation into the effect of changing the criterion from Gini Impurity to Information Gain. The scores were plotted against one another on a line graph.

## Task 3

Two more investigations into changing the parameters of the DT classifier were conducted. This time we changed the min_samples and max_depth parameters.
