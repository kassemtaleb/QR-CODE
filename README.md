# QR Code Generator

A simple QR Code Generator built with Node.js.

## Features
- Get a URL from the user using Inquirer.
- Generate a QR Code image using qr-image.
- Save the generated QR Code as `qr_img.png`.
- Save the entered URL in `URL.txt`.

## Technologies Used
- Node.js
- Inquirer
- qr-image
- File System (fs)

## Installation

1. Clone the repository.
2. Install dependencies:

```bash
npm install
```

3. Run the project:

```bash
node index.js
```

4. Enter your URL when prompted.

## Output
- `qr_img.png` – Generated QR Code.
- `URL.txt` – Saved URL.
