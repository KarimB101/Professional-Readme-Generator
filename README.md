# Professional README Generator 

## User Story

```md
AS A developer
I WANT a README generator
SO THAT I can quickly create a professional README for a new project
```

## Acceptance Criteria

```md
GIVEN a command-line application that accepts user input
WHEN I am prompted for information about my application repository
THEN a high-quality, professional README.md is generated with the title of my project and sections entitled Description, Table of Contents, Installation, Usage, License, Contributing, Tests, and Questions
WHEN I enter my project title
THEN this is displayed as the title of the README
WHEN I enter a description, installation instructions, usage information, contribution guidelines, and test instructions
THEN this information is added to the sections of the README entitled Description, Installation, Usage, Contributing, and Tests
WHEN I choose a license for my application from a list of options
THEN a badge for that license is added near the top of the README and a notice is added to the section of the README entitled License that explains which license the application is covered under
WHEN I enter my GitHub username
THEN this is added to the section of the README entitled Questions, with a link to my GitHub profile
WHEN I enter my email address
THEN this is added to the section of the README entitled Questions, with instructions on how to reach me with additional questions
WHEN I click on the links in the Table of Contents
THEN I am taken to the corresponding section of the README
```
## Description 
Here is a link on what a Professional README should typically include along with some tips on what is optional based on your application [How to create a Professional README](https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide). 
This code will use Node so that any user can create a readme file from the command line itself. There will be a series of questions of what the user can input for the required parts of the readme. If other aspects want to be added the user can simply add them if necessary. This code should help users build a standard README by simply inputing their necessary information. Installing node and the necessary inquirer files are required and shows the benefit of having such a program.

## Installation 
The inquirer package will preferably be needed before running the code through Node.
Here is a link on how to install Node [Guide on How to install Node](https://coding-boot-camp.github.io/full-stack/nodejs/how-to-install-nodejs)
A link on how to install the Inquirer package and its file modules is summarized on this site [Inquirer package](https://www.npmjs.com/package/inquirer/v/8.2.4) as the current version used is version 8.2.4.
'npm i inquirer@8.2.4' would be the command on the command line to install this package. 

## Usage

## Credits

## License
MIT License

Copyright (c) 2022 KarimB101

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Project Status
The application is currently functional and all the standard inputs that deem to be necessary for a professional have been included. If enough suggestions for more or different inputs to be included into the readme generator the code may be updated within a reasonable timeframe. 


