# hvacmaintreport
input values, output job summary
I was trying to write a function that printed out an array of strings plus
	the int values from the form. I was trying to get it to output into the paragraph below,
	but I couldn't get that to work. So I went with the document write function to output 
	on a new page. At first I couldn't get it to display the string and int on the same line,
	so I wrote the outputs in two separate functions and it started working. 

	Later I got rid of the document write and started using innerHTML.

	Another issue I had was getting it to pull the int value from the form and assign it to 
	the variables I declared, but then I realized I assigned the ID to the label instead of 
	the input.
  
  backticks allow string interpolation for better looking array
  
  can't figure out how to add line spacing. \n breaks code.
  trying to find some way to format js output in the html 
  
  getting two commas in output. 
		might try array within array to interpolate string and var
		(issue resolved after using backticks)
    
    the user input displays the way I intend if I put all of it as an array
