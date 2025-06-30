# Selenium Automation - Contact Form Testing

Automated UI test for the contact form on [seleniumframework.com/lander](https://www.seleniumframework.com/lander) using Java, Selenium WebDriver, and TestNG.

## 🔧 Tools & Technologies
- Java 17+
- Selenium WebDriver 4.x
- TestNG
- Maven
- IntelliJ IDEA
- Page Object Model (POM)

## 🚀 Project Structure
src/

├── main/

│ └── java/

│ └── pages/

│ └── LanderPage.java

│ └── utils/

│ └── WebDriverManager.java

├── test/

│ └── java/

│ └── tests/

│ └── LanderPageTest.java

│ └── testdata/

│ └── SampleData.java


## 🧪 What This Test Does
- Launches Chrome browser
- Opens the contact page
- Switches to iframe
- Fills in name, email, and message
- Submits the form

## ✅ How to Run
Make sure you have:
- ChromeDriver installed and path configured in `WebDriverManager.java`
- JDK 17 or later installed
- Maven installed

Then run the test using:
```bash
mvn test
