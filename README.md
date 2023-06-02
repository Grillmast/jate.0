## jate.0 - Text Editor Web Application
jate.0 is a text editor web application that allows you to create notes or code snippets with or without an internet connection. It meets the criteria of a Progressive Web App (PWA) and offers various features to enhance your text editing experience.

## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [Features](#features)
* [Contributing](#contributing)
* [License](#license)
## Installation
To install and run jate.0 on your local machine, follow these steps:

Clone the repository:
Copy code
```
git clone <repository-url>
```
Navigate to the project's root directory:
Copy code
```
cd jate.0
```
Install the required dependencies using npm:
Copy code
```
npm install
```
## Usage
To start using jate.0, follow these steps:

Open your preferred text editor and navigate to the project's root directory.
Run the following command to start the backend and serve the client:
Copy code
```
npm run start
```
Access the text editor application from your browser by visiting the provided URL.

## Features
* Client-server folder structure.
* Bundling of JavaScript files using webpack.
* Generation of HTML file, service worker, and manifest file using webpack plugins.
* Support for next-gen JavaScript without browser compatibility issues.
* Immediate creation of IndexedDB database storage upon opening the text editor.
* Auto-saving of content to IndexedDB when clicking off the DOM window.
* Retrieval of saved content from IndexedDB when reopening the text editor.
* Installation of the web application as an icon on the desktop.
* Registration of a service worker using workbox for offline functionality.
* Pre-caching of static assets upon loading, including subsequent pages and assets.

## Contributing
Contributions to jate.0 are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue on the GitHub repository or submit a pull request.

## License
This project is licensed under the MIT License.
