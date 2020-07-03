# EmployeeSummary
[![NPM Version Badge](https://badge.fury.io/js/%40angular%2Fcore.svg)](https://badge.fury.io/js/%40angular%2Fcore)

## Table of Contents
*  [Description](##description)
*  [License](#license)
*  [Contributing](#contributing)
*  [Questions](#questions)
## Description
[Repository](https://github.com/bfiles3/EmployeeSummary)
This assignment was to create an app in command line that would use input to create an HTML page that consists of employees on a development team. There is three categories, which are all employees: Manager, Engineer, and Intern. They all have specific questions that are related to their position, and they all have to be saved and rendered to the HTML page.

The first task was to create a package.json using npm's init function in command line. After the package was created, I created a class for each employee, and a constructor within those classes to hold the information. I created a function in the employee file to export the common questions between all the employees. I then created specific functions in each individual employee page that related to their individual titles and questions that are specific to those particular employees.
![](/Assets/ss1.png)

Following the creation and exporting of individual employee pages, I began working on the app.js file, trying to work in the order I wanted the app to run. I attempted several different ways to get the questions to appear in the way that I wanted, but unforunately, in the end, the only way I could get the questions to appear for each employee was to repeat the questions in a function related to each employee. I originally wanted to make one singular function to represent all of the questions, having the specific questions for each employee only appear when they are chosen, but eventually I could not get them to render correctly and had to break them down into individual functions.
![](/Assets/ss2.png)

After I got the questions to appear in the correct order and in relation to the correct employees, I created a function to save the input and then bring in the classes from each of the employee JavaScript pages. Lastly, I created the function to prompt the user to either add a new employee, or append the information to the HTML page. 
!][](/Assets/ss3.png)

# License
MIT License

Copyright (c) [2020] [Brittany Files]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

# Contribution
There were no contributers on this project. Any code references were used from in-class activities. 

# Questions
If there are any questions, feel free to reach out on [GitHub](https://github.com/bfiles3)
