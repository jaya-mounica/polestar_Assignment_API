# Playwright API Testing
For Polestar Project created API Test Cases 

## Features
- Reading data from json / enum files
- creating Dynamic data using faker files
- allure report


## Project structure
.github -> yml file to execute the tests in GitHub Actions
test-results -> Contains all the reports related file

## Reports
- allure report
- Logs

***Get Started Setup:***

- Clone or download the project
- Extract and open in the VS-Code
- npm i to install the dependencies
- npx playwright install to install the browsers
- npm run test to execute the tests
          
Use tags to run a specific or collection of specs

```
npx playwright test 
```
***Folder structure***

src\pages ->   All the page (UI screen)
                                        
src\test -> write your features here 

test-data ->  Add json request in the file





























Pre-Condition:
Need to install VS code in local machine
Need to have access to the Git Repository

Steps to Follow:
Clone the folder from the Git Repository
Open Terminal from the Menu
Select New Terminal
Type 'cd tests' in the Terminal and hit enter from the keyboard
Now Type 'npx playwright test' and hit enter from the keyboard
After getting the status 
Type npx allure serve allure-results
check the status report
