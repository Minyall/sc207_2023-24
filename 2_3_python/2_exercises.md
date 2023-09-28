# Python Fundamentals - Lab Exercises
Create a new cell for each question.

## Section 1
### Exercise 1.1
What is the answer to `(5/2) * (6+1)`?

### Exercise 1.2
Create a variable called `love` and assign it the value of `We all love ` as a string

Create another variable called `mascot` and assign it the value of `Campus Cat` as a string.

Join the two variables together to create a single sentence. Once you've finished experiment with changing the value of `mascot` to change the final result.


### Exercise 1.3 

Use the appropriate string method to make the value of `mascot` all upper case.

### Exercise 1.4
Create a variable called `next_mascot` and assign it the value of `Our new mascot is Campus Dog` as a string.

Let's change our mind and replace `Dog` with `Duck`, but we'll do it using the appropriate string method. Google what the appropriate python string method would be to replace a word in a string. 

See if you can implement it so that our new mascot is `Campus Duck`.

### Exercise 1.5
Fix the following code so that it is an f-string that announces the change of university mascot.

`"Today we announce that {} will take over from {} as the new university mascot!"`

---

## Section 2

Here is a small extract from a recent news story

```
"Ex-PM Boris Johnson has been given permission to build a swimming pool in his Oxfordshire home, despite initial concerns it could impact nearby newts."
```
Source: https://www.bbc.co.uk/news/uk-politics-66938308

### Exercise 2.1
Create a variable called `text`  and assign it the string of text above.

### Exercise 2.2
Use Google (or other sources) to find the appropriate string method to split up a piece of text into individual words. Assign the resulting list to a variable called `words`

### Exercise 2.3
Use list indexing to find the 4th item in `words`

### Exercise 2.4
Use a list index range to find the last item in `words` (tip you do not need to know how many items are in the list).

### Exercise 2.5
The built in function `len()` will tell you the number of characters in a string. For example:
```
len('Hello')
>> 5
```
Create a new list variable called `long_words`. Use a loop to iterate over the list of `words` and append only words that are longer than 5 characters to the `long_words` list.
