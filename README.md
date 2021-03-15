# team-profile-generator

## Table of Contents: 
* Description 
* First Look 
* Technologies Used
* Installation 
* License 
* References 

## Description:
I created an app that generates a team profile by prompting the user to fill out information about their team manager and team members. The user can also input any number of team members with varying roles (i.e. engineers & interns) 

## First Look: 
![Team Profile Generator](https://user-images.githubusercontent.com/69092983/111232314-dd682a00-85b8-11eb-9631-90d0c0accf78.png)

## Technologies Used:
* [InquirerJS](https://www.npmjs.com/package/inquirer)
* [Jest](https://jestjs.io/) 

## Installation:
First, you will need to clone the repository onto your current working directory. Then, you will need to do an ```npm i``` into your terminal in order to install all of your dependencies. I used the following directory structure to create my application: 

```
lib/           // classes and helper code
output/        // rendered output
templates/     // HTML template(s)
test/          // jest tests
  Employee.test.js
  Engineer.test.js
  Intern.test.js
  Manager.test.js
app.js         // Runs the application
```

## License: 
MIT License

Copyright (c) [2021] [Amber Chiodini]

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

## References: 
* [Stack Overflow](https://stackoverflow.com/) 
* [Object-oriented JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object-oriented_JS)