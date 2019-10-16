# Reflection

## Question 1 (50 words)
#### When and why should you use a function like `carefulSubract` rather than `subtract`? 
### You would want to use a more specific function like 'carefulSubtract', rather than 'subtract', if you have a particular condition that you would like to pass through the function. For example, in 'carefulSubtract' you're only subtracting the parameters if both of them are numbers. If you were to use another data type the function would return an error. 


## Question 2 (100 words)
#### What are `data types`, and how does data typing work in JavaScript? Name at least 4 built-in data JS data types. 
### Data types are built-in variables that store information; which is dependent on the programming language you are using. When you use one of these variables in Javascript, it tells the computer what to look for and what to return. For example, in the question 'subtract' we used the data-type 'number'. This specifically tells the computer to look for numerical values and run the function accordingly. If we were to pass through variables that are not numbers then the code would pass back an error message. Some of the other data types are: string, boolean, null, array, and object.

## Question 3 (100 words)
#### What is the advantage to storing information as an object (`{firstName: 'Italo', lastName: 'Calvino', profession: 'novelist' }`) rather than as an array (`['Italo', 'Calvino', 'novelist']`)? Are there any disadvantages?

### Storing information in an object can be useful if you have a property that you want to set to a particular variable. An advantage to using objects is that they pass through more specific properties, like someones first name. In contrast, arrays pass through multiple elements, that resemble an ordered list. An example of an array could be the different schools a person went to. Consequently, arrays would be more useful if you have multiple elements. You can also easily add elemenets to an array by using push() or remove the last array by using pop(). Arrays also provide a sequenced order to your elements, whereas objects do not.  

## Question 4 (150 words)
#### The function `sentences` transforms a data structure (in this case, a list of object literals) into a sequence of sentences. If the data structure were less predictable (e.g., if some properties of each object were occasionally missing, or if their data type was not always the same), what programming techniques could you use to ensure that your function produced a coherent output? Also, can you think of a more interesting "transform" that could be done with the same data structure?

### One technique would be to insert conditional statements using if or else statements. This would still allow your code to return an output even if the user didn't fill out all of the information. A second technique would be to use the 'case' statement, which would allow for multiple expressions of the value. A more interesting way may be to use the prompt() method to get your user to continue filling out their information. Depending on your code, this could be a fun and interactive way of corresponding with the user. It would also ensure you are getting the right properties from users so that your function is able to work as designed. A second interesting technique would be to use the 'switch' statement. This is a control mechanism that would change the the program direction depending on what the user inputted. This could be very beneficial to something with multiple choices and answers, like a survey. 

