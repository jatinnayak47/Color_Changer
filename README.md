# Color_Changer
JavaScript Background Color Switcher

A simple project to switch the background color of a web page by clicking on color buttons. This project uses HTML, CSS, and JavaScript to demonstrate event handling and DOM manipulation.

Features

Four color options: Grey, White, Blue, and Yellow.

Clickable buttons to change the background color dynamically.

Minimal and responsive design.

Folder Structure

project-directory
|
|-- index.html        # Main HTML file
|-- style.css         # CSS for basic styling
|-- chaiaurcode.js    # JavaScript file to handle color switching
|-- styles.css        # (Optional) Additional CSS file

Prerequisites

Ensure you have the following installed:

Node.js (for running a local server, if needed)

Visual Studio Code (or any code editor)

Steps to Run the Project

1. Clone the Repository

If you are using GitHub, clone the repository:

git clone <repository-url>

Alternatively, download the zip file and extract it to your desired directory.

2. Open in Visual Studio Code

Open the project folder in Visual Studio Code.

3. Run the Project Locally

You can run the project directly in your browser by opening the index.html file. However, using a local server is recommended to avoid any CORS-related issues.

To use a local server:

Install the live-server npm package globally:

npm install -g live-server

Navigate to the project folder:

cd project-directory

Start the server:

live-server

This will automatically open the project in your default browser.

4. Dependencies

No external libraries or frameworks are required for this project. However, you may optionally use live-server for easier local testing.

File Descriptions

index.html

The main HTML file contains:

Four <span> elements with unique ids (grey, white, blue, yellow) for the color buttons.

A basic structure with navigation links and headings.

style.css

Contains styles for:

Buttons (span elements) with different background colors.

Layout and responsiveness.

index.js

The JavaScript file contains:

Event listeners for the buttons to change the background color of the page dynamically based on the clicked button's id.

How It Works

The buttons are selected using document.querySelectorAll('.button').

Event listeners are added to each button.

When a button is clicked, its id is used to set the background color of the <body> element dynamically.

Example Output

When you click a button, the background color of the page changes to the respective color (Grey, White, Blue, or Yellow).

Additional Notes

If you want to add more colors, simply add more <span> elements in index.html with appropriate ids and CSS styles.

Ensure the JavaScript file is correctly linked in the <script> tag in index.html.

Issues or Suggestions

Feel free to raise issues or contribute to improving the project!

