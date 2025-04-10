Project 3.3 
	In this project you will generate the HTML code for a web table displaying the top 10 movies from the IMDB website. Information on each movie is stored in arrays that have been created for you. Your job will be to create a program loop that loops through the content of the arrays and writes information as new table rows in the web table. A preview of the completed project is shown in figure 3-20. 
 
1. Use your code editor to open the project03-03_txt.html and project03-03_txt.js files from the js03 project03 folder. Enter your name and the date in the comment section of each file and save them as project03-03.html and project03-03.js. 
2. Go to the project03-03.html file in your code editor and in the head section add a script element to load the project03-03.js file, deferring the loading of the JavaScript source file until the entire HTML file is loaded. Study the contents of the HTML file and save your changes. 
3. Go to the project03-03.js file in your code editor. Below the code that creates and populates the links array, declare the htmlCode variable, settings its initial value to an empty text string. 
4. Create a for loop with a counter that goes from 0 to less the length of the titles array in increments of 1. With each iteration, add the following text to the value of the htmlCode variable:

See book for html code steps
<tr>
<td><a href=’links[i]’>titles[i]</a><td>
<td>summaries[i]</td>
<td>ratings[i]</td>
</tr>
Where i is the value of the counter for that iteration, and links[i], titles[i], summaries[i], and ratings[i] are the values from the corresponding elements in the links, titles, summaries, and ratings arrays. 
5. After the for loop, declare a variable named tableBody referencing the first and only element in the web document with the tag name “tbody”.
6. Change the innerHTML property of tablebody to the value of the htmlCode variable. 
7. Save your changes to the file and then load project03-03.html in your browser. Verify that the page displays the top 10 movies in the IMDB ratings.

