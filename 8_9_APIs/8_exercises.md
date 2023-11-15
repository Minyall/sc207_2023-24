# 8 - APIs  - Lab Exercises
Create a new cell for each question.

## For Information
The basic web address ENDPOINT to interact with the Guardian API is below. You will need this for your code.


## Section 1
### Exercise 1.1
Make a simple request for data to the Guardian API using just your API key as a parameter.

### Exercise 1.2
Make another request, but this time set a query parameter of the phrase `"University of Essex"`.

### Exercise 1.3
Make another request using the same query, but this time ensure that all results come from the `society` section of The Guardian. To do this you will need to work out what parameter name specifies the section you want to search. Take a look at the Guardian API 'Filters' documentation linked in the starter notebook (after accessing the link you will need to scroll down to the 'Filters' heading).

---

## Section 2
Building an automated collector. It is recommended that you refer to the PDF notes for this lab while completing this section.
### Exercise 2.1
Start by setting up the basic logic for your collector. Create the while loop that will first adjust the current page number in your parameters, print the parameters, increment the page count by 1 and then sleep for 1 second before looping round again. Ensure your while loop will stop after a specified maximum amount of pages.
### Exercise 2.2
Now fill in the collector with actual steps for data collection. 
- Rather than print the parameters, you should make a request to the API with them.
- Ensure you take the results of that request, and add them to your list of results that sits outside of the while loop.
- You should ask the API response how many pages are available so you can update your variable that tracks that info so your collector doesn't stop prematurely.
- For your own peace of mind, you should print out a little message explaining what page your collector has collected, how many pages are available, and anything else you might want it to say.
- Crucially, your collector should then sleep for at least 1 second, if not a few, before it returns to the beginning of the while loop where it will check that all the conditions are still True, before running the process again.
