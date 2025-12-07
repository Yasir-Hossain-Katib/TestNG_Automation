# TestNG Automation
## Project Description
This project is an automated testing suite for the web application hosted at Daily Finance. The objective is to ensure the key functionalities of the application, such as user registration, password reset, item addition, profile updates, and admin functionalities, are working as expected. The tests include both positive and negative scenarios to validate the robustness and reliability of the application.

## Prerequisites
Before running the tests, ensure you have the following set up:

**System Requirements:**
- Operating System: Windows/Mac/Linux
- JDK (Java Development Kit) installed (Version 8 or above)
- Browser drivers installed (e.g., ChromeDriver for Chrome)

**Tools and Frameworks:**
- Selenium WebDriver
- TestNG for test management
- Gradle for dependency management

**Credentials:**
- A valid Gmail account to test email-related functionality.
- Admin credentials for the application (to be securely passed from the terminal).

**Dependencies:**
- Update the ```build.gradle``` file with required libraries such as Selenium, TestNG, and Rest Assured API libraries.


## How to Run the Tests
Follow these steps to execute the automated tests:

- Clone the Repository
    - ```git clone <repository-url>```
- Set Up the Environment
    - Install dependencies using Gradle
- Configure Credentials
    - Update the config.properties file with Gmail credentials and other necessary details.
    - Pass admin credentials securely when prompted by the terminal during execution.
- Run the Tests
    - Command: ```gradle clean test -Pemail="Email" -Ppassword="Password"```
- View Test Reports

## Test Case Link
[https://docs.google.com/spreadsheets/d/16mj-HPobFJfvYhj-rGrcFOyjd7sx9_BVEOnQePDU-3c/edit?usp=sharing](https://docs.google.com/spreadsheets/d/1hXeXNsRZxHLtOdFZoXvBcp_Eah7-mptidm60NWsajMQ/edit?gid=0#gid=0)

## Reports:
![image](https://github.com/user-attachments/assets/7d371151-50c6-4c2b-bc6a-45adcc32d5c9)


![image](https://github.com/user-attachments/assets/e36201d4-292c-4227-9f22-c5f104dc02f6)


## Sample Video of Automation Process

https://github.com/user-attachments/assets/a06f21f8-c81b-4450-90da-4aad84973702

