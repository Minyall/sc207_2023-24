# 7 - Data Visualisation - Lab Exercises
Create a new cell for each question.

## Setup
If starting a new notebook, ensure you have run the following code.
```
import seaborn as sns
titanic_df = sns.load_dataset('titanic')
titanic_df['pclass'] = titanic_df['pclass'].astype('category')
titanic_df['alive'] = titanic_df['alive'].astype('category')
titanic_df['n_family'] = titanic_df['parch'] + titanic_df['sibsp']

```

## Section 1
### Exercise 1.1
Using Seaborn and your `titanic_df` dataframe, create a histogram to show the distribution of `n_family`. Do you need to adjust the `binwidth`?

### Exercise 1.2
Make the same plot as above, but this time use a KDE and colour it by `pclass`. What does this tell us about family membership and class on the ship?

### Exercise 1.3
Question: Is there a notable class difference in the average number of family members a person would have with them. Does this change with passenger gender? Can you display this in a single plot?

---

## Section 2
### Exercise 2.1

Does travelling with family have an impact upon likelihood of survival? Create a `lmplot` that provides a logistic regression showing survival outcome dependent on number of family members.

### Exercise 2.2
Does your conclusion about survival and number of family members change if you introduce passenger class as a dimension to your visual? Split the plot using `pclass` in some way that supports your comparison of different classes.

### Exercise 2.3
Does your conclusion about survival change if you introduce gender as a deminseion to your visual? Split the plot further using `sex`. Does it make a difference to your interpretation if you choose to split using colour, or using columns or rows?

### Exercise 2.4
Try making a `pairplot` using a subset of the datatset columns `['survived','pclass','sex','age','n_family']`. Check the seaborn documentation for pairplots to see what options you have for the `kind=` argument and the `diag_kind=` argument. Experiment with them alongside splitting data by `hue` to see what kind of quick insights can be generated.
