# QR Code Generator using Node.js

This project is a simple QR Code Generator built with JavaScript and Node.js. It allows users to enter a URL through the command line and automatically generates a QR code image along with a text file containing the entered URL.

## Features

* Takes user input using the `inquirer` package
* Generates a QR code image using the `qr-image` package
* Saves the QR code as `qr_img.png`
* Stores the entered URL in a text file named `URL.txt`

## Technologies Used

* JavaScript
* Node.js
* npm packages:

  * `inquirer`
  * `qr-image`
  * `fs` (Node.js File System module)

## Installation

1. Install Node.js from
   [Node.js Official Website](https://nodejs.org?utm_source=chatgpt.com)

2. Clone the project or download the files.

3. Install the required npm packages:

```bash
npm install inquirer qr-image
```

## Project Structure

```plaintext
project-folder/
│
├── solution.js
├── qr_img.png
├── URL.txt
└── package.json
```

## How to Run

Run the following command in the terminal:

```bash
node solution.js
```

Then enter a URL when prompted:

```bash
Type in your URL:
```

After entering the URL:

* A QR code image will be generated as `qr_img.png`
* The URL will be saved in `URL.txt`

## Example

Input:

```bash
https://www.google.com
```

Output:

* `qr_img.png` → QR code image
* `URL.txt` → Contains the entered URL

## Future Improvements

* Add custom QR code colors
* Create a web-based interface
* Allow users to download QR codes in different formats

