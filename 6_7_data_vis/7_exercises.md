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



