2022-12-13
Tags:

# Alchemy University
## Intro to JS
### The Basics

    * Javascript is run-time compilation
    * JS add automatically ";" at the end of a line, that's why you are not 
        froce to put one.`
    * JS is tend to be written in lowerCamelCase
    * "`" can be used to add variable to the string like this: 
        '''
        const helloMessage = `Hello ${anotherName}, my name is ${myName}!`;
        '''`
    * Parameters are the name of the input, arguments are the value of the inputs
    * the function splice() allow to manipulate an ArrayList by removing value 
        and reshap the arraylist. if you need to loop around that operation
        prefer counting backwards since it might modify the length of the array
    * it's better to use '===" than "==" because the second will do try to convert
        before compareing (and it's less performant than the first one) 
    * item JSON need to be in "", not ''
    * we can distructer in JS: 
       ` '''
            const obj = {
                  a: 2,
                  b: 3,
                  }
        
            // destructure assignment
            const { a, b } = obj;
            
            console.log(a); // 2
            console.log(b); // 3
        '''`
     * we can reste in JS: use ...arg to get an array of the argument pass in a 
        funtion
     * We can bind() function in JS, and those var can't be overwritten
     * Need to be carefull how where and how to use this in object (see Alchemy
        course 1-Classe and Property -> This Keyword and Unbond chapter)
        This seems tricky in callback function, need to be aware on what 'this'
        is pointing. Which context (function, global ...)
     * The Class in JS are not the same as a typical OOP language. Here we talk
        about Property, and each new instance of a Prototype share the same set
        of function comming from Object.prototye. (It's chained)
     * We can call new on function(), it will understand that it's prototype and
        'new' will bind 'this' to the instance created from object. careful with
        () => {} in those
     * while inheriting class, if we want to access 'this' we need to call 
        super() first in the constructor.
### Data Structure

     * When using the sort() function on an arry of int, need to pass the cmp 
        we want to do in to sort it right. sinon it will convert it to string 
        first
     * reduce() on array is very powerful for reformating complex array into new
        object
---
# References
