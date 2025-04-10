Project 3.5 
	In this debugging challenge you will fix the mistakes in a program that generates a horizontal bar chart describing the relative sales of five brands of cell phones sold by a company. You can use the browser console to evaluate the code and the arrays the program uses to locate any errors. When the code has been fixed, it will display a bar chart shown in figure 3-22. The horizontal bar chart is created by generating a web table with each phone model displayed on a separate table row. The bars themselves are generated using <td></td> tags with the number of td elements in each row equal to the percentage of the total sales to the nearest 1%. For example a phone that accounts for 40% of the sales will have 40 td elements in its table row. The width and color of each td element is set in a style sheet so that different background colors are applied to different phone models. 
 
1. Use your code editor to open the project03-05_txt.html and project03-05_txt.js files from the js03 project05 folder. Enter your name and the date in the comment section of each file and save them as project03-05.html and project03-05.js.
2. Go to the project03-05.html file in your code editor and in the head section add script element to load the project03-05.js file, deferring the loading of the JavaScript source file until the entire HTML file is loaded. Study the contents of the HTML file and save your changes.
3. Go to the project03-05.js file in your code editor. Comments have been added to help you understand the code used in this application.
4. Locate and fix the following errors in the code:
   
a. The program declares two arrays named phones and sales that contain the names of five phone models and their units sold. There is an error in declaring each of these arrays. Locate and fix those errors 

b. The program uses the foreach() method with the addToTotal() function as the callback function to calculate the total sales across all phone models. Fix the error in the statement that runs the forEach() method. 

c. In the for loop that writes the td element for the bar chart there are errors defining the counter values. Locate and fix the errors involved. 

d. Fix the error in the statement that declares and initializes the barPercent variable. 

e. Fix the syntax errors in the switch statement that sets the value of the cellTag variable based on name of the phone method.

f. At the end of the for loop the program inserts the value of the barChart variable into HTML code of the first <body> element in the document, directly before the closing </tbody> tag. Locate and fix the error in this statement. 

5. Save your changes to the file and then open project03-05.html in your web browser. Verify that the bar chart is generated as shown in figure 3-22. If you start getting errors, use the browser console to help you locate and fix errors in the code. 

