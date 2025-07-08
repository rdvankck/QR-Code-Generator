# QR-Code-Generator


A simple command-line tool built with Node.js to instantly generate a QR code from a user-provided URL. The tool saves the QR code as a PNG image and logs the URL into a text file.

Features
Interactive URL Input: Uses inquirer to prompt the user for a URL in the command line.

QR Code Generation: Employs qr-image to create a QR code image from the given URL.

URL Logging: Saves the entered URL to a URL.txt file for future reference using Node.js's native fs module.

Getting Started
These instructions will get you a copy of the project up and running on your local machine.

Prerequisites
You need to have Node.js and npm (Node Package Manager) installed on your system. You can check for their installation by running:

node -v
npm -v

Installation
Clone the repository or download the source code into a local directory.

Navigate into the project directory:

cd your-project-directory

Install the necessary npm packages:

npm install inquirer qr-image

Usage
Run the application from your terminal:

node index.js

You will be prompted to enter a URL. Type or paste the URL and press Enter.

? QR icin site giriniz! (Enter a site for the QR!) › https://www.google.com

Once you submit the URL, the script will perform two actions:

Generate a qr_img.png file in the root directory.

Create or overwrite a URL.txt file containing the URL you entered.

You will see a confirmation message in the console:

The file has been saved!

Built With
Node.js - The JavaScript runtime environment.

Inquirer.js - A collection of common interactive command line user interfaces.

qr-image - A library for generating QR codes.

Contributing
Contributions are welcome! If you have suggestions for improving this project, please feel free to fork the repository and submit a pull request.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request
