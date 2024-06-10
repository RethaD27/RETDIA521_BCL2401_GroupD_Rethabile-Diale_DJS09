# DJS09: Couch Surfing | Typescript Practice

# Property Review Application
Overview
This Property Review Application is a simple web application that displays a list of properties, their reviews, and additional information about the user. It allows users to see the properties, their details, and the top two reviews for each property.

## Features
Display a list of properties with images and prices.
Show the total number of reviews and the last reviewer.
Highlight if the user is a returning user.
Display a main property with an image and reviews.
Provide an interactive button to show top reviews.
Show current location in the footer.
File Structure
python
Copy code
.
├── index.html
├── index.css
├── index.ts
├── enums.ts
├── interfaces.ts
├── types.ts
├── utils.ts
├── classes.ts
├── images/
│   ├── colombia-property.jpg
│   ├── polish-cottage.jpg
│   ├── london-flat.jpg
│   ├── malaysian-hotel.jpeg
│   ├── italian-property.jpg
│   ├── sofa-logo.png
├── dist/
│   ├── index.pack.js
Getting Started
Prerequisites
Node.js and npm should be installed on your system.
TypeScript should be installed globally.
Installation
Clone the repository to your local machine:

bash
Copy code
git clone <repository-url>
Navigate to the project directory:

bash
Copy code
cd property-review-application
Install the dependencies:

bash
Copy code
npm install
Compile the TypeScript files:

bash
Copy code
tsc
Open index.html in your browser to see the application in action.

Usage
HTML Structure
index.html: Contains the HTML structure of the application.
nav-bar: Contains the logo and user welcome message.
container: Main content area that includes:
main-image: Displays the main property image.
reviews: Shows the review total and last reviewer.
button: Button to fetch and display reviews.
properties: Displays the list of properties.
footer: Displays the current location.
CSS Styling
index.css: Contains the CSS styles for the application.
TypeScript Code
index.ts: Main script file that handles the application logic.
enums.ts: Defines the enumerations used in the application.
interfaces.ts: Defines the interfaces used for typing the data.
types.ts: Contains additional types used in the application.
utils.ts: Contains utility functions like showing review total, populating user details, and showing property details.
classes.ts: Defines the MainProperty class.
Commit Messages
Ensure your commit messages are clear and concise. Example:

kotlin
Copy code
feat: Add MainProperty class with constructor
License
This project is licensed under the MIT License.

Acknowledgments
The project uses images and icons from various free resources.
Thanks to the open-source community for providing excellent tools and libraries.
 
