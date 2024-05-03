# nickefr.github.io
https://nickefr.github.io/
⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
# WorkAround Explorer - Front-End Development

WorkAround Explorer is a web application designed to provide users with easy access to salary data trends in the tech industry. Developed by WorkAround, a research organization, this tool aims to offer insights into salary information based on specific roles and companies within the tech sector.

## Overview

The WorkAround Explorer web app allows users to select a role and a company from the tech industry to view various salary-related data points, including:

- The salary for the chosen role at the chosen company.
- The industry average salary for the chosen role.
- The average salary at the chosen company across all roles.
- The industry average salary across all roles and all companies.

Upon selecting a role and a company, the relevant data is dynamically displayed, providing users with valuable insights into salary trends within the tech industry.

## Getting Started

To use WorkAround Explorer, simply follow these steps:

1. Navigate to the website: [WorkAround Explorer](https://nickefr.github.io/workaround-explorer/)
2. Select a role from the first column.
3. Select a company from the second column.
4. View the relevant salary data displayed in the third column.

## Implementation Details

### Rendering Radio Buttons

The rendering of radio-style `<input>` elements for companies and roles is facilitated by the `renderInputButtons()` function in `main.js`. This function accepts arrays of labels for companies and roles and dynamically generates the corresponding input elements.

### Data Calculation and Display

The calculation and display of salary-related data are handled by the `workAroundModule.js` module. This module contains functions that calculate various data values based on user selections. The calculated data is then rendered to the screen using the `updateResults()` function in `main.js`.

### Modular Approach

WorkAround Explorer employs a modular approach to ensure clear separation of concerns. The `salaryData.js` module provides access to raw salary data, while the `workAroundModule.js` module handles data manipulation and calculation. This modular structure enhances code organization and maintainability.

## Tasks

### Completed Tasks

- [x] Export functions from `salaryData.js` using ES6 named export syntax.
- [x] Import `getRoles` and `getCompanies` functions into `main.js` and initialize variables.
- [x] Specify `main.js` as a module in `index.html` to enable module usage.
- [x] Import necessary functions and data from `salaryData.js` into `workAroundModule.js`.
- [x] Complete functions in `workAroundModule.js` to calculate data values.
- [x] Export functions from `workAroundModule.js` using named export syntax.
- [x] Import functions from `workAroundModule.js` into `main.js`.
- [x] Update `updateResults()` function in `main.js` to calculate and render data based on user input.

### Extra Challenge

As an extra challenge, a utility function `formatNumber()` has been implemented in `utilities.js` to format numerical values with commas. This function is imported into `main.js` and used to format the rendered data values.



---

By implementing a modular architecture and leveraging import and export functionalities, WorkAround Explorer offers users a seamless experience for exploring salary data in the tech industry. For any inquiries or feedback, please contact the WorkAround team.

