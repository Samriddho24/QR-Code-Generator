# 🔳 QR Code Generator

A simple Node.js application that generates QR codes from user-provided URLs. The application accepts a URL through the terminal, creates a QR code image, and stores the entered URL in a text file.

## 📸 Preview

### Generated QR Code 

![QR Code](Screenshots/Screenshot1.png)
 
### Saved URL File

![Saved URL](Screenshots/Screenshot2.png)

## 🚀 Features

* Accepts URL input from the terminal
* Generates QR code images instantly
* Saves entered URLs to a text file
* Uses Node.js native modules and npm packages
* Beginner-friendly Node.js project

## 🛠️ Technologies Used

* Node.js
* Inquirer
* QR-Image
* File System (fs)

## 📂 Project Structure

```text
QR-Code-Generator/
├── index.js
├── package.json
├── package-lock.json
├── README.md
├── .gitignore
└── screenshots/
    ├── qr-preview.png
    └── url-preview.png
```

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/Samriddho24/QR-Code-Generator.git
```

Navigate to the project directory

```bash
cd QR-Code-Generator
```

Install dependencies

```bash
npm install
```

## ▶️ How to Run

Run the application

```bash
node index.js
```

Enter a URL when prompted:

```text
https://google.com
```

The application will:

* Generate a QR code image
* Save the entered URL into a text file
