# Team Profile Generator

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Tests](#tests)
- [Questions](#questions)
- [Demo](#demo)
- [License](#license)

## Description
This application will generate an HTML page of your team. The page that is generated includes the following:

- One Manager

- Engineers

- Interns

With important contact information as their name, employee id and their email address.

There is more info returned depending on the role the user selects:

- Manager includes a office number (numbers only)

- Engineer includes a github username

- Intern includes a school name 

## Installation
To run:

- All the packages should be included, but if needed, run `npm install`, `npm install inquirer`, `npm install fs` & `npm install colors`

- Open a terminal in the root folder and run `node app.js`

- You will be asked a series of questions based on your selections. 

- Use the arrow keys to select which role you would like to enter.

- Choose 'list complete' when you are finished adding team members

- The resulting html file saves into the output directory as "output.html"

**Example of Finsihed Team Profile:**
![screenshot1](./demo/team-screenshot.png)

- The style.css file is included with the example styling above, but you may use your own design to fit your needs.

## Tests
To run the tests type `npm test` (uses jest)

![screenshot2](./demo/test-screenshot.png)

## Questions
If you have questions, feel free to contact me at hello@susieotto.com

## Demo
### **Running The App**
![Demo](./demo/demo-run-app.gif)

### **Adding Manager**
![capture1](./demo/demo-manager.gif)
### **Adding Engineers**
![capture2](./demo/demo-engineer.gif)
### **Adding Interns**
![capture3](./demo/demo-intern.gif)
### **Saving Your Team Profile**
![capture4](./demo/demo-list-complete.gif)
)

## License
None

