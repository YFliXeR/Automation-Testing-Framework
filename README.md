# 🧪 Ecommerce Automation Framework

This project is a **Selenium-based automation testing framework** developed during my internship at **Atos**.  
It’s designed to automate and validate key user workflows on an e-commerce web application, following industry-standard testing practices.

---

## 🚀 Features
- **Page Object Model (POM)** structure for modular, maintainable test scripts  
- **TestNG** integration for test execution and organization  
- **Extent Reports** for detailed HTML reporting  
- **Driver Manager** utility for handling browser sessions  
- Reusable **helper methods** for actions, assertions, and random data generation  

---

## 🧩 Tech Stack
- **Language:** Java  
- **Frameworks:** Selenium, TestNG  
- **Build Tool:** Maven  
- **Reporting:** Extent Reports  
- **Design Pattern:** Page Object Model (POM)  

---

## 🧠 Project Structure
src/
├── main/
│ ├── java/
│ │ ├── pages/ # Page Object Model classes
│ │ ├── utiles/ # Helper classes (DriverManager, Reports, etc.)
│ │ └── tests/ # TestNG test classes
├── testng.xml # Test suite configuration
└── pom.xml # Maven dependencies

---

## 🧰 How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/YFliXeR/Ecommerce-Automation-Framework.git
2. Open in an IDE (Intellij)
3. Run the test suite via testng.xml
4. View the generated Extent Report under /reports.
