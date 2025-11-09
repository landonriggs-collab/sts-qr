# STS QR Generator

## Overview
The STS QR Generator is a web application that allows users to generate QR codes from a specified URL. The application features a dark-themed interface with a centered card layout, making it user-friendly and visually appealing.

## Project Structure
```
sts-qr
├── index.html          # HTML markup for the QR generator page
├── styles.css         # CSS styles for the dark theme and layout
├── src
│   ├── main.js        # Main JavaScript file for application logic
│   └── qr-lib.js      # QR code generation logic
├── package.json       # npm configuration file
├── .gitignore         # Files and directories to ignore in Git
└── README.md          # Documentation for the project
```

## Features
- Dark-themed interface
- Centered card layout
- Input field for URL
- QR code generation
- Download options for SVG and PNG formats

## Setup Instructions
1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd sts-qr
   ```
3. Install dependencies:
   ```
   npm install
   ```
4. Open `index.html` in your browser to view the application.

## Usage
- Enter a URL in the input field.
- Click the "Generate" button to create the QR code.
- Use the "Download SVG" or "Download PNG (hi-res)" buttons to save the QR code in your desired format.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any suggestions or improvements.

## License
This project is licensed under the MIT License.