# Quick_ApplyIn
Easily automate the process of applying for jobs on LinkedIn with this tool!

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

1. **Install Selenium**

   Use pip to install the Selenium package:

   ```bash
   pip install selenium
2. **Download a WebDriver**

Selenium requires a driver to interface with the chosen browser. Ensure the driver is in your system's PATH and add your driver_path to the config.json file.

I used the Chrome driver. You can also download drivers for Edge, Firefox, or Safari, depending on your preferred browser.

### Usage

  **Fork and Clone the Repository**

  Fork and clone/download the repository to your local machine.

### Configuration
Create a `config.json` file with the following structure:

    ```json
          {
          "email": "your_linkedin_email",
          "password": "your_linkedin_password",
          "keywords": "Machine Learning Engineer, Data Scientist",
         "location": "Your Location",
         "driver_path": "/path/to/your/webdriver"
          }
**Run the Script**

  Execute the script by running:

  ```bash
    python main.py
