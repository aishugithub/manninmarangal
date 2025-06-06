# Mannin Marangal Project

## Overview
This project, titled "Mannin Marangal," is designed to identify trees based on leaf images captured through a webcam. It utilizes a machine learning model trained to recognize various tree species.

## Project Structure
The project consists of the following files:

- **model/model.json**: Contains the architecture of the machine learning model, including the layers and their configurations.
- **model/weights.bin**: Contains the weights for the model, which are necessary for making predictions.
- **model/weights_1.bin**: Contains additional weights for the model, possibly for different layers or configurations.
- **model/weights_2.bin**: Contains further weights for the model, similar to the previous weights files.
- **mainpage.html**: The main HTML page for the project, which includes the user interface and JavaScript code to load the model and make predictions based on webcam input.
- **manifest.json**: Used for web app configuration, specifying metadata about the app.
- **README.md**: This documentation file, which provides setup instructions and usage guidelines.

## Setup Instructions
1. **Clone the Repository**: 
   Clone this repository to your local machine using:
   ```
   git clone <repository-url>
   ```

2. **Install Dependencies**: 
   Ensure you have the necessary libraries and frameworks installed. This project uses TensorFlow.js for model loading and predictions.

3. **Load the Model**: 
   The model files are located in the `model` directory. Ensure that the paths in `mainpage.html` are correctly set to load the `model.json` and associated weights files.

4. **Run the Application**: 
   Open `mainpage.html` in a web browser. Allow camera access when prompted to start identifying tree species.

## Usage Guidelines
- Point your webcam at a leaf, and click the "Identify Tree" button to get predictions.
- If the model is unsure, it will prompt you to contribute additional information about the tree.

## Testing
After making any changes to the model or the code, thoroughly test the application to ensure that it functions as expected. Check for any errors in the console and handle them appropriately.

## Contribution
If you would like to contribute to this project, please follow the guidelines outlined in the application. Your contributions will help improve the model and expand its capabilities.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.