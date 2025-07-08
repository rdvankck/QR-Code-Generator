````markdown
# QR Code Generator

A simple command-line tool built with Node.js to instantly generate a QR code from a user-provided URL. The tool saves the QR code as a PNG image and logs the URL into a text file.

## Features

- **Interactive URL Input**: Uses [inquirer](https://www.npmjs.com/package/inquirer) to prompt the user for a URL in the command line.
- **QR Code Generation**: Employs [qr-image](https://www.npmjs.com/package/qr-image) to create a QR code image from the given URL.
- **URL Logging**: Saves the entered URL to a `URL.txt` file for future reference using Node.js's native `fs` module.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites

You need to have Node.js and npm (Node Package Manager) installed on your system. You can check for their installation by running:

```bash
node -v
npm -v
````

If not installed, follow the [official installation guide](https://nodejs.org/).

### Installation

1. Clone the repository or download the source code into a local directory:

```bash
git clone https://github.com/rdvankck/QR-Code-Generator.git
cd qr-code-generator
```

2. Install the necessary npm packages:

```bash
npm install inquirer qr-image
```

### Usage

1. Run the application from your terminal:

```bash
node index.js
```

2. You will be prompted to enter a URL. Type or paste the URL and press Enter.

```bash
? QR icin site giriniz! (Enter a site for the QR!) › https://www.google.com
```

3. Once you submit the URL, the script will perform two actions:

* Generate a `qr_img.png` file in the root directory.
* Create or overwrite a `URL.txt` file containing the URL you entered.

4. You will see a confirmation message in the console:

```bash
The file has been saved!
```

## Built With

* **Node.js**: The JavaScript runtime environment.
* **Inquirer.js**: A collection of common interactive command line user interfaces.
* **qr-image**: A library for generating QR codes.

## Contributing

Contributions are welcome! If you have suggestions for improving this project, feel free to fork the repository and submit a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

```
