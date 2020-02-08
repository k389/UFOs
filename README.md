# UFOs
JavaScript, Bootstrap, CSS, VS Code

# Project Overview/Challenge
- Create, update, and diploy JavaScript functions. 
	- filters include date, city, statem country and shape from the data.
- Update and deploy forEach(for loop) to loop through the filters and update the table based on user input.
- Update and populate the dynamic filters and table using JavaScript and HTML.

# Resources
- Data Source: data.js
- Software: Visual Studio Code, 1.40.2., Google Chrome, JavaScript, Bootstrap

# Summary
- Practice
	- Used VS Code to create JavaSpript and HTML to deploy UFO page. 
	- UFO HTML page displays a header with image, an article and a data table.
	- The data table displays data from data.js using JavaScript function.
	- The date filter is created to filter the data table based on user date entry.
	- the date filter is created using JavaScript function. 
	- JavaScript methods used are:
		- forEach to create the data table.
		- if else statement to filter the data table based on the date.
		- d3.selectAll().on() to listen to the form button 
	- Customized the HTML page using style.css to display image in the header, to change the background and text color and align text.
- Challenge
	- Updated the filters to add additional filters besides date - city, state, country and shape.
		- updated the HTML to include the additional filters to the list. 
		- updated the app.js code to be able to use the additional filters to filter through the data.
	- Created new function to filter the table
		- used forEach to loop through the filters and display data that matches the filter values.
	- Used d3.selectAll().on() to attach event listener to pick up changes and use the Filter Table button.
- Further Recommendation
	- The page is using one data source (data.js), which can be limited. 
	- the developer can update the page by finding news articles (other current resources) and scarape the data to display on the page. This will give the most current infromation on the topic.
	- the developer also can also can customize the page to have the background change every time it is refreshed instead of having one background image. 

