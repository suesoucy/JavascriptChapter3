Project 3.4
	In this project you will display a customer reviews for a new digital game. Information on each customer and review is contained within several arrays. Customers give the game a rating from one to five stairs, which you will display as star images in the web page. A preview of the completed project is shown in figure3-21. 
 
1. Use your code editor to open the project03-04_txt.html and project03-04_txt.js files from the js03 project04 folder. Enter your name and the date in the comment section of each file and save them as project03-04.html and project03-04.js. 
2. Go to the project03-04.html file in your code editor and in the head section add a script element to load the project03-04.js file deferring the loading of the JavaScript source file until the entire HTML file is loaded. Study the contents of the HTML file and save your changes. 
3. Go to the project03-04.js file in your code editor. At the bottom of the file, insert a function named starImages() with a single parameter named rating. The purpose of the function is to generate the HTML tags of several star images based on the value of the rating parameter. 
4. Within starImages() function add the following

a. Declare a variable named imageText setting its initial value to an empty text string.

b. Create a for loop with a counter that goes from 1 up to less than or equal to the value of the rating parameter, increasing the counter by 1 with each iteration.

c. In the for loop, add the text “<img src= ‘star.png’ alt= “>”to the value of the imageText variable with each iteration.

d. After the for loop, add a statement to return the value of imageText from the function. 

5. Create a for loop with the counter variable ranging from 0 up to less than the length of the reviewers array increasing the counter by 1 with each iteration. In this for loop you will generate the HTML code for a table that contains the review from each customer. 
6. For each iteration within the for loop, do the following:
   
a. Declare a variable named reviewCode setting its initial value to an empty text string. 

b. Insert an else if statement that adds one of three possible text strings to the value of reviewCode: if the value of reviewType for the current element in the array is equal to “P” then add the text string “<table class=’prime’>” else if the value of the reviewType for the current element is equal to “N” then add the text string”, “<table class =’new’>” else add the text string “<table>”. 

c. Add the following HTML code to the value of the reviewCode variable (Need to see book for html code)
<caption>reviewTitles[i]</caption>
<tr><th>By</th><td>reviewers[i]</td></tr>
<tr><th>Review Date</th><td>reviewDates[i]</td></tr>
</table>

d. Use the insertAdjacentHTML() method to insert the value of the reviewCode variable into the first and only <article> tag in  the document, placing it directly before the closing tag. 

7. Save your changes to the file and load project03-04.html in your web browser, verify that all four reviews are shown as indicated in figure 3-21.

