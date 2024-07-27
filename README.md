# NMC Function Calculator

## Description
The NMC Function Calculator is a simple web application that calculates the new MAS (Mass) based on the Deviation Index (x) and the Old MAS (y). This project is designed to help students and professionals easily compute these values on the go.

## How to Use
1. Open the [NMC Function Calculator](https://your-username.github.io/nmc-function-site) in your web browser.
2. Enter the value for the Deviation Index (x).
3. Enter the value for the Old MAS (y).
4. Click the "Calculate" button to see the new MAS.

## Technical Details
This project consists of an HTML form that collects user inputs for the Deviation Index (x) and the Old MAS (y). It uses JavaScript to send these inputs to a Google Cloud Function, which performs the calculation and returns the result.

### HTML and JavaScript
The main functionality is implemented in the `index.html` file, which includes:
- A form for user inputs.
- A script to handle form submission, send data to the Google Cloud Function, and display the result.

### Google Cloud Function
The Google Cloud Function takes the input parameters (x and y), performs the calculation, and returns the new MAS. The function is accessible via an HTTP endpoint.

## Repository Structure
