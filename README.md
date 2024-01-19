# Exercise 9 - Case 3

## Instructions:
1. Use your editor to open the ja_vynes_txt.html and ja_quote_txt.js files from the html09 > case3 folder. Enter your name and the date in the comment section of each file, and save them as ja_vynes.html and ja_quote.js respectively
2. Go to the ja_vynes.html file in your editor. Directly above the closing </head> tag, insert a script element that links the page to the ja_quote.js file. Defer the loading of the script file until the rest of the page is loaded by the browser
3. Study the contents of the file and then save your changes
4. Go to the ja_quote.js file in your editor. At the top of the file, insert a statement indicating that the code will be handled by the browser assuming strict usage
5. Directly below the comment section, insert a function named randomlnt that will be used to generate a random integer. Specify two parameters for the function named lowest and size. The lowest parameter will specify the lowest possible value for the random integer and the size parameter will set the number of integers to be generated. Use those two parameter values and the Math.floor() and Math.random() methods to return a random integer within the specified range
6. Above the randomlnt() function insert a command to call the function, generating a random integer from 0 to 9. (Hint: Remember that the size of this interval is 10 because it includes 0 in its range.) Store the result from the function in the randomQ variable
7. Create a variable named quoteElem that references the first element in the document that has the quote tag name
8. Call the getQuote() function using the randomQ variable as the parameter value to generate a random Jane Austen quote. Display the text of the quote as the inner HTML code of the quoteElem variable
9. Add appropriate comments to your code to document your work
10. Save your changes to the file and then open the ja_vynes.html file in your browser. Verify that a random Jane Austen quote appears at the top of the 
11. Reload the page several times and verify that with each reloading, a different Austen quote appears on the page
