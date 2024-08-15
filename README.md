# 🎓 Student Management System MangoDB

Welcome to the **Student Management System**! This web-based application is built using the MERN (MongoDB, Express.js, React.js, Node.js) stack and aims to streamline school management, class organization, and facilitate communication between students, teachers, and administrators.

## 📚 About

The Student Management System is designed to help schools manage their operations efficiently. It provides functionalities for different user roles, including Admin, Teacher, and Student, each with specific access levels and capabilities.

## ✨ Features

- **User Roles:** 
  - 👨‍💼 **Admin:** Manage students, teachers, classes, subjects, and system settings.
  - 👩‍🏫 **Teacher:** Take attendance, assess performance, and communicate with students.
  - 👨‍🎓 **Student:** View marks, track progress, and communicate with teachers.

- **Admin Dashboard:** 
  - Add new students and teachers.
  - Create classes and subjects.
  - Manage user accounts and system settings.

- **Attendance Tracking:** 
  - Mark students as present or absent.
  - Generate attendance reports.

- **Performance Assessment:** 
  - Provide marks and feedback.
  - Students can view their marks and track their progress.

- **Data Visualization:** 
  - Interactive charts and tables for students to visualize their performance data.

- **Communication:** 
  - Effortless communication between teachers and students.

## 🛠️ Technologies Used

- **Frontend:** React.js, Material UI, Redux
- **Backend:** Node.js, Express.js
- **Database:** MongoDB

## 🚀 Installation

Follow these steps to set up the project locally:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/Yogndrr/MERN-School-Management-System.git
    ```

2. **Setting Up Backend:**
    - Open a terminal and navigate to the backend folder:
        ```sh
        cd backend
        npm install
        npm start
        ```
    - Create a [`.env`](command:_github.copilot.openSymbolFromReferences?%5B%22.env%22%2C%5B%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22c%3A%5C%5CUsers%5C%5CTalha%20PC%5C%5CTAS_MAN%5C%5CStudent-Management-System-MangoDB%5C%5CTAS_MAN%5C%5Cbackend%5C%5Cindex.js%22%2C%22_sep%22%3A1%2C%22external%22%3A%22file%3A%2F%2F%2Fc%253A%2FUsers%2FTalha%2520PC%2FTAS_MAN%2FStudent-Management-System-MangoDB%2FTAS_MAN%2Fbackend%2Findex.js%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2FTalha%20PC%2FTAS_MAN%2FStudent-Management-System-MangoDB%2FTAS_MAN%2Fbackend%2Findex.js%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A8%2C%22character%22%3A20%7D%7D%2C%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22c%3A%5C%5CUsers%5C%5CTalha%20PC%5C%5CTAS_MAN%5C%5CStudent-Management-System-MangoDB%5C%5CTAS_MAN%5C%5CREADME.md%22%2C%22_sep%22%3A1%2C%22external%22%3A%22file%3A%2F%2F%2Fc%253A%2FUsers%2FTalha%2520PC%2FTAS_MAN%2FStudent-Management-System-MangoDB%2FTAS_MAN%2FREADME.md%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2FTalha%20PC%2FTAS_MAN%2FStudent-Management-System-MangoDB%2FTAS_MAN%2FREADME.md%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A49%2C%22character%22%3A21%7D%7D%2C%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22c%3A%5C%5CUsers%5C%5CTalha%20PC%5C%5CTAS_MAN%5C%5CStudent-Management-System-MangoDB%5C%5CTAS_MAN%5C%5CREADME.md%22%2C%22_sep%22%3A1%2C%22external%22%3A%22file%3A%2F%2F%2Fc%253A%2FUsers%2FTalha%2520PC%2FTAS_MAN%2FStudent-Management-System-MangoDB%2FTAS_MAN%2FREADME.md%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2FTalha%20PC%2FTAS_MAN%2FStudent-Management-System-MangoDB%2FTAS_MAN%2FREADME.md%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A72%2C%22character%22%3A31%7D%7D%5D%5D "Go to definition") file in the backend folder and add your MongoDB URL:
        ```sh
        MONGO_URL = mongodb://127.0.0.1/school
        ```

3. **Setting Up Frontend:**
    - Open another terminal and navigate to the frontend folder:
        ```sh
        cd frontend
        npm install
        npm start
        ```
    - Navigate to [`localhost:3000`](command:_github.copilot.openSymbolFromReferences?%5B%22localhost%3A3000%22%2C%5B%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22c%3A%5C%5CUsers%5C%5CTalha%20PC%5C%5CTAS_MAN%5C%5CStudent-Management-System-MangoDB%5C%5CTAS_MAN%5C%5Cfrontend%5C%5CREADME.md%22%2C%22_sep%22%3A1%2C%22external%22%3A%22file%3A%2F%2F%2Fc%253A%2FUsers%2FTalha%2520PC%2FTAS_MAN%2FStudent-Management-System-MangoDB%2FTAS_MAN%2Ffrontend%2FREADME.md%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2FTalha%20PC%2FTAS_MAN%2FStudent-Management-System-MangoDB%2FTAS_MAN%2Ffrontend%2FREADME.md%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A11%2C%22character%22%3A13%7D%7D%2C%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22c%3A%5C%5CUsers%5C%5CTalha%20PC%5C%5CTAS_MAN%5C%5CStudent-Management-System-MangoDB%5C%5CTAS_MAN%5C%5CREADME.md%22%2C%22_sep%22%3A1%2C%22external%22%3A%22file%3A%2F%2F%2Fc%253A%2FUsers%2FTalha%2520PC%2FTAS_MAN%2FStudent-Management-System-MangoDB%2FTAS_MAN%2FREADME.md%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2FTalha%20PC%2FTAS_MAN%2FStudent-Management-System-MangoDB%2FTAS_MAN%2FREADME.md%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A63%2C%22character%22%3A18%7D%7D%5D%5D "Go to definition") in your browser to view the frontend.

## 🐞 Error Solution

If you encounter an error while signing up, either a network error or a loading error that goes on indefinitely, follow these steps:

1. Navigate to the [`frontend > .env`](command:_github.copilot.openSymbolFromReferences?%5B%22frontend%20%3E%20.env%22%2C%5B%7B%22uri%22%3A%7B%22%24mid%22%3A1%2C%22fsPath%22%3A%22c%3A%5C%5CUsers%5C%5CTalha%20PC%5C%5CTAS_MAN%5C%5CStudent-Management-System-MangoDB%5C%5CTAS_MAN%5C%5CREADME.md%22%2C%22_sep%22%3A1%2C%22external%22%3A%22file%3A%2F%2F%2Fc%253A%2FUsers%2FTalha%2520PC%2FTAS_MAN%2FStudent-Management-System-MangoDB%2FTAS_MAN%2FREADME.md%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2FTalha%20PC%2FTAS_MAN%2FStudent-Management-System-MangoDB%2FTAS_MAN%2FREADME.md%22%2C%22scheme%22%3A%22file%22%7D%2C%22pos%22%3A%7B%22line%22%3A72%2C%22character%22%3A20%7D%7D%5D%5D "Go to definition") file.
2. Uncomment the first line.
3. Terminate the frontend terminal.
4. Open a new terminal and execute the following commands:
    ```sh
    cd frontend
    npm start
    ```

## 📄 License

This project is licensed under the MIT License. See the [`LICENSE`](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FC%3A%2FUsers%2FTalha%20PC%2FTAS_MAN%2FStudent-Management-System-MangoDB%2FLICENSE%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\Talha PC\TAS_MAN\Student-Management-System-MangoDB\LICENSE") file for details.

## 📞 Contact

For any inquiries or issues, please contact us at [support@example.com](mailto:support@example.com).

---

Thank you for using the Student Management System! We hope it helps you manage your school operations efficiently. 🎉