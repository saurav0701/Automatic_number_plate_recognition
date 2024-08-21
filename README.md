# MATLAB Calculator App

## Overview

This MATLAB project is a simple calculator app created using MATLAB's App Designer. The app allows users to perform basic arithmetic operations and bitwise operations between two inputs. The results are displayed within the app.

## Files in the Repository

- **`calcsaurav.m`**: The main MATLAB app file that contains the logic for the calculator.
- **`input-file.png`**: A screenshot showing the input panel of the app where users can enter parameters.
- **`output-file.png`**: A screenshot showing the output panel of the app displaying the calculation results.

## How to Open and Run the Code

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/saurav0701/Automatic_number_plate_recognition.git
   cd calculator-app
2. **Open MATLAB**:

- Launch MATLAB on your system.

### Open the App File:

1. In MATLAB, navigate to the directory where the repository was cloned.
2. Open the `calcsaurav.m` file by either:
   - Double-clicking it in the MATLAB file browser.
   - Typing `open('calcsaurav.m')` in the MATLAB command window.

### Run the App:

- Click the "Run" button in the MATLAB editor.
- Or type `calcsaurav` in the command window to launch the app.

## Code Explanation

### Class Definition:

- The app is defined as a class named `calcsaurav`, which inherits from `matlab.apps.AppBase`.
- The app's properties include various UI components such as panels, text areas, and buttons.

### UI Components:

- **UIFigure**: The main figure window that contains the entire app.
- **ResultPanel**: Contains the output display area.
- **OutputTextArea**: Displays the result of the calculations.
- **InputsbyuserPanel**: Contains the input text areas for the two numbers.
- **Input1TextArea** and **Input2TextArea**: Text areas where users input their numbers.
- **OperatorsPanel**: Contains buttons for various arithmetic and bitwise operations.

### Callback Functions:

- **ButtonPushed**: Adds the two inputs and displays the result.
- **Button_2Pushed**: Subtracts the second input from the first and displays the result.
- **Button_3Pushed**: Multiplies the two inputs and displays the result.
- **Button_4Pushed**: Divides the first input by the second and displays the result.
- **Button_5Pushed**: Performs the AND bitwise operation on the two inputs and displays the result.
- **Button_6Pushed**: Performs the OR bitwise operation on the two inputs and displays the result.
- **Button_7Pushed**: Performs the NOT bitwise operation on the first input and displays the result.
- **XORButtonPushed**: Performs the XOR bitwise operation on the two inputs and displays the result.
- **Button_8Pushed**: Concatenates the two inputs as strings and displays the result.

### Error Handling:

- Basic error handling is included by converting string inputs to double precision using `str2double`. 
- If the input is not a number, MATLAB will return `NaN` and the app will handle this by displaying an appropriate message in the output area.

## Input and Output Screenshots

### Input Panel:

The input panel allows users to enter the necessary parameters for the vehicle simulation.

![Input Panel](/input-file.png)

### Output Panel:

The output panel displays the results of the simulation based on the provided inputs.

![Output Panel](/output-file.png)

## Requirements

- MATLAB (version R2019b or later)

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you'd like to change
