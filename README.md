# Domain URL & JS Extractor for Burp Suite

## Overview

The **Domain URL & JS Extractor** is a Burp Suite extension that allows users to specify domains and automatically extracts relevant URLs and JavaScript files from HTTP requests and responses. This tool is especially useful for penetration testers and security researchers looking to analyze web applications.

## Features

- **Domain Filtering**: Enter domains with wildcards (e.g., `*.example.com`) to filter extracted URLs.
- **URL Extraction**: Extracts URLs from JSON payloads and HTML responses.
- **JavaScript Extraction**: Identifies and lists all JavaScript files referenced in the web application's HTML.
- **User-Friendly UI**: Intuitive interface within Burp Suite for easy domain management and result viewing.

## Installation

1. Ensure you have [Burp Suite](https://portswigger.net/burp) installed.
2. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/domain-url-js-extractor.git
Open Burp Suite and go to the Extender tab.
Click on the "Add" button to load the .py file from the cloned repository.
Usage
Navigate to the "Domain & JS Extractor" tab within Burp Suite.
Enter a domain (e.g., *.example.com) in the input field and click "Add Domain."
Start intercepting HTTP requests/responses. Matched URLs and JavaScript files will be displayed in their respective sections.
Code Structure
BurpExtender Class: Implements the core functionality, including domain management and HTTP message processing.
UI Components: Built using Java Swing for a responsive user experience.
Requirements
Burp Suite Professional or Community Edition.
Python environment compatible with Jython (for running Python scripts in Burp).
Contributing
Contributions are welcome! Feel free to open issues or submit pull requests for enhancements.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Author
Fighter001

### GitHub Project Description

**Domain URL & JS Extractor** is a Burp Suite extension that extracts URLs and JavaScript files from HTTP requests and responses based on specified domains, aiding in web application security assessments.

Feel free to customize the content to better fit your project's specific details, such as your name and GitHub link!
