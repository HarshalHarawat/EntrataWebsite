# EntrataWebsite

This repository contains automated tests for the Entrata website using Selenium WebDriver and TestNG.
 
# Prerequisites
 
Before running the tests, make sure you have the following installed:
 
1. Java Development Kit (JDK) - Ensure JDK is installed and configured properly on your system.
2. Maven - Make sure Maven is installed on your system. You can download it from [here](https://maven.apache.org/download.cgi) and follow the installation instructions.
3. Chrome WebDriver - Download the Chrome WebDriver compatible with your Chrome browser version and place it in the specified directory.
 
# Running the Tests
 
Follow these steps to run the automated tests:
 
1. Clone the repository to your local machine:
 
   ```bash
   git clone <repository_url>
   ```
 
2. Navigate to the project directory:

   cd <project_directory>
  
3. Open the project in your preferred IDE (Eclipse, IntelliJ, etc.).
 
4. Make sure all dependencies are resolved.
 
5. Update the Chrome WebDriver path in the `MaincodeTest` class:
 

System.setProperty("webdriver.chrome.driver", "<path_to_chrome_driver>");

 
6. Execute the tests by running the `MaincodeTest` class as a TestNG test.
 
7. After execution, view the test results in the console. Any failures will be reported along with the reason.
 
# Notes
 
- The tests are designed to run on Chrome browser. Make sure you have Chrome installed on your system.
- Ensure a stable internet connection during test execution as it interacts with live web pages.
- If needed, update the implicit wait time and other parameters according to your testing requirements in the test setup.
