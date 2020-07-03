# EmployeeSummary

## Description
This assignment was to create an app in command line that would use input to create an HTML page that consists of employees on a development team. There is three categories, which are all employees: Manager, Engineer, and Intern. They all have specific questions that are related to their position, and they all have to be saved and rendered to the HTML page.

The first task was to create a package.json using npm's init function in command line. After the package was created, I created a class for each employee, and a constructor within those classes to hold the information. I created a function in the employee file to export the common questions between all the employees. I then created specific functions in each individual employee page that related to their individual titles and questions that are specific to those particular employees. 

Following the creation and exporting of individual employee pages, I began working on the app.js file, trying to work in the order I wanted the app to run. I attempted several different ways to get the questions to appear in the way that I wanted, but unforunately, in the end, the only way I could get the questions to appear for each employee was to repeat the questions in a function related to each employee. I originally wanted to make one singular function to represent all of the questions, having the specific questions for each employee only appear when they are chosen, but eventually I could not get them to render correctly and had to break them down into individual functions.

After I got the questions to appear in the correct order and in relation to the correct employees, I created a function to save the input and then bring in the classes from each of the employee JavaScript pages. Lastly, I created the function to prompt the user to either add a new employee, or append the information to the HTML page. 

