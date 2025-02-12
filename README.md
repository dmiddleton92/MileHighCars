# MileHighCars

    ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Description

    MileHighCars is an application that prompts users to either create an existing vehicle or create a vehicle. After creating or selecting a vehicle the user is able to perform several actions such as start and turn off car or accelerate and more. After user is finished with actions they may exit the application. 
## Table of Contents 

- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## User Story
    As a developer I want to update an existing application to include additional vehicle types so that I am able to understand and work with existing code. 

## Acceptance Criteria
- GIVEN a command-line application that accepts user input
- WHEN I am prompted to create a new vehicle or existing vehicle, THEN I can choose between the two options
- WHEN I am prompted to choose the vehicle type during creation, THEN I can choose between car, truck, and motorbike
- WHEN I am prompted for details about the vehicle, THEN I can enter the vehicle information
- WHEN I have entered all the vehicle information, THEN I can use the created vehicle
- WHEN I select an existing vehicle, THEN I can use the selected existing vehicle
- WHEN I have created a new vehicle or selected an existing vehicle, THEN I can perform actions with that vehicle
- WHEN I perform an action with a vehicle, THEN I see the result of the action in the command-line
- WHEN I complete the process of performing an action, THEN I can perform additional actions until I choose to exit

## Resources
    https://www.typescriptlang.org/docs/handbook/intro.html

## Technologies
    Node.js
    Typescript

## Features
    Command Line prompts; CREATE,SELECT Vehicle
    Three vehicle types: Car, Truck, Motorbike
    Each vehicle has a list of commands 

## Installation
    In order to use this application you must install Node.js, typescript and inquirer before running program.
    -install node.js: [Link](https://nodejs.org/en/download/package-manager)
    -install inquirer: [Link](https://www.npmjs.com/package/inquirer)
    -install typescript: [LINK](https://www.typescriptlang.org/download/)

## Usage
    Clone my repository and install the following packages listed above. After that is done run the command 'npm run start'. Once that is done you will have a list of prompt questions then a set of actions. When done creating or selecting vehicle you can print details of that vehicle and perform actions. Motorbike and truck have actions specific to those vehicles. 

## Walkthrough Video
    Here is a video to watch to see how this application is demonstrated

## Contributors

    Dylan Middleton

## License
![License](https://img.shields.io/badge/License-MIT-yellow.svg "License")
This project is licensed under the [MIT](https://opensource.org/licenses/MIT) license.


