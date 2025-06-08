# 🧮 Simple Calculator

This is a basic calculator web application built with **Spring Boot (Java)** for the backend and **HTML/JavaScript** for the frontend.

---

## 🚀 Features

- Perform basic arithmetic operations: **Addition**, **Subtraction**, **Multiplication**, **Division**
- User-friendly UI to input operator and numbers
- Backend REST API using Spring Boot
- Input validation and error handling

---

## 🛠️ Technologies Used

- Java (Spring Boot)
- HTML, JavaScript
- Maven (build tool)

---

## 🧪 How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/aditya-divyam/Simple-Calculator.git
cd Simple-Calculator
### 2. Start the Spring Boot server
bash
Copy
Edit
mvn spring-boot:run
### 3. Open in your browser
Visit http://localhost:8080 to use the calculator.

## 📦 Project Structure
css
Copy
Edit
Simple-Calculator/
├── src/
│   └── main/
│       ├── java/
│       │   └── com/example/Calculator/
│       │       ├── CalculatorApplication.java
│       │       └── CalculatorController.java
│       └── resources/
│           └── static/
│               └── index.html
├── pom.xml
└── README.md
## 🔁 Sample API Endpoints
Operation	Endpoint	Example
Addition	/api/add?a=5&b=3	Returns 8
Subtraction	/api/subtract?a=5&b=3	Returns 2
Multiplication	/api/multiply?a=5&b=3	Returns 15
Division	/api/divide?a=6&b=2	Returns 3

## 👤 Author
Aditya Divyam
GitHub: @aditya-divyam

## 📄 License
This project is open-source and available under the MIT License.

sql
Copy
Edit

This is the full text for the `README.md` file. Just copy the entire text and paste it into your `README.md` file in your project. Once done, commit and push it to GitHub:

```bash
git add README.md
git commit -m "Add proper README file"
git push
