QR Code Generator using Node.js
This project is a command-line application built using Node.js that takes a user-provided URL as input, generates a QR code for that URL, and saves the generated QR code as a .png image file. Additionally, the URL is stored in a .txt file for record-keeping purposes. The project demonstrates the use of multiple npm packages and Node.js core functionality, making it an excellent showcase of practical backend development skills.

Key Features:
Interactive User Input: The application prompts the user to input a URL via the command line, making it user-friendly and interactive.
QR Code Generation: Once the URL is provided, the application uses the qr-image npm package to generate a QR code and save it as qr_img.png.
File System Operations: The user-provided URL is stored in a URL.txt file using Node.js's built-in fs module, demonstrating file handling capabilities.
Error Handling: Basic error handling is included to manage issues like missing user input or file writing errors.

Project Dependencies:
Node.js: The runtime environment used for the project.
inquirer (v9.3.6): A popular npm package used to prompt users for input in the terminal.
qr-image (v3.2.0): A package for generating QR codes in image format.
fs: The native Node.js file system module used to handle file reading and writing.

Setup and Usage:
Clone this repository to your local machine.
Run npm install to install the required dependencies.
Execute the application by running node index.js.
When prompted, input the desired URL.
The generated QR code will be saved as qr_img.png in the project directory, and the URL will be stored in URL.txt.

Future Enhancements:
Add support for multiple QR code formats.
Implement a web interface for easier usage.
This version expands on the project’s functionality, setup instructions, and adds potential future enhancements, providing more detail for recruiters to assess your skills.


[![Project Demo](https://img.youtube.com/vi/6tOrjQPXuzY/0.jpg)](https://youtu.be/6tOrjQPXuzY)
![Screenshot (13)](https://github.com/user-attachments/assets/b2dcb0eb-d7f9-45cb-a9d2-e92d3ad90e92)


![Screenshot![Screenshot (13)](https://github.com/user-attachments/assets/cb718869-b6d2-4bdf-aede-dc6d5d3ca944)
![Screenshot (14)](https://github.com/user-attachments/assets/d8e9212b-b631-4ef6-9c74-0cc2a50acac8)
 (14)](https://github.com/user-attachments/assets/9d07550a-654a-4661-8c11-6b002da1ac78)

