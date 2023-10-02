# 3 - Python Fundamentals - Lab Exercises
Create a new cell for each question.

## Section 1
### Exercise 1.1
Create a simple function called `double`. The `double` function should have one argument called `number`. The function should take `number`, multiply it by two and then `return` the result.

### Exercise 1.2

Take a look at this code:
```
first_name = 'Scooby'
surname = 'Doo'
job = 'Detective'

first_name + ' ' + surname + ' is a ' + job
> 'Scooby Doo is a Detective'
```

Create a function called `say_job`. `say_job` should take three arguments, `first_name`, `surname` and `job`. It should join the words together into a sentence like the code above, and then `return` the result.

Test your function to see what `say_job` says if you pass in different values to the arguments.

### Exercise 1.3 

Adjust your `say_job` function so that it has an optional argument called `exclaim` with the default value of `False`. Then add some code that checks the value of `exclaim`, and if it is `True`, it will add an exclamation mark `!` to the end of the sentence.

### Exercise 1.4
Next week we're going to be using the [Pandas](https://pandas.pydata.org/) library. The main object we'll use is called a `DataFrame`. Do you think you could find the documentation for the `DataFrame`'s `.info` method? How many arguments does it take. How many are optional?

