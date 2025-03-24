
# ✅ TodoList Web Application

### 📌 Overview
The **TodoList Web Application** is a Java-based task management system that allows users to create, update, and manage their daily tasks efficiently.

---

## 🚀 Features  
✅ **User Registration & Login** – Secure authentication system  
✅ **Task Management** – Add, update, delete, and mark tasks as completed  
✅ **Database Integration** – Persistent task storage using MySQL  
✅ **Servlets & JSP** – Backend powered by Java Servlets  
✅ **Maven Project Structure** – Easy dependency management  

---

## 🛠️ Technologies Used  
- **Java** – Backend logic  
- **JSP & Servlets** – Web application handling  
- **MySQL** – Database for storing tasks  
- **Maven** – Dependency and build management  
- **Bootstrap & CSS** – Frontend styling  

---

## 📂 Project Structure  
```
📁 TodoList/
 ├── 📜 pom.xml  # Maven dependencies
 ├── 📂 src/main/java/
 │   ├── 📂 beans/   # Java Beans (Register, Task)
 │   ├── 📂 dao/     # Data Access Object (ToDoDAO, ToDoDAOImpl)
 │   ├── 📂 factory/ # Database Connection Factory (DBConn)
 │   ├── 📂 servlets/ # Servlet Controllers (AddTaskServlet, LoginServlet, LogoutServlet)
 ├── 📂 src/main/webapp/
 │   ├── 📜 index.jsp  # Home Page
 │   ├── 📜 login.jsp  # Login Page
 │   ├── 📜 register.jsp  # User Registration
 │   ├── 📜 dashboard.jsp  # Task Dashboard
 │   ├── 📜 styles.css  # Styling
```

---

## 🚀 How to Run  
### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/Vamshi-Bejjanki/TodoList.git
cd TodoList
```

### **2️⃣ Configure Database**
- Create a **MySQL database**:  
  ```sql
  CREATE DATABASE todolist;
  ```
- Update `DBConn.java` with your database credentials.  
- Run the SQL script to create tables.

### **3️⃣ Build & Run the Application**
- Use **Maven** to build:
  ```sh
  mvn clean install
  ```
- Deploy the `war` file to **Tomcat Server**.  

---

## 📌 API Endpoints (Servlets)
| **Servlet**        | **URL**                | **Function** |
|-------------------|----------------------|-------------|
| `LoginServlet`    | `/login`             | User Login |
| `RegisterServlet` | `/register`          | User Registration |
| `AddTaskServlet`  | `/addTask`           | Add a New Task |
| `DeleteTaskServlet` | `/deleteTask`       | Delete a Task |
| `LogoutServlet`   | `/logout`            | User Logout |

---

## 📝 Future Enhancements  
- 📱 **Mobile Responsive UI**  
- 🔔 **Email & Push Notifications**  
- 🗂 **Task Categorization**  
- 🌐 **Multi-language Support**  

---

## 🎯 Contribution  
Want to contribute? Follow these steps:  
1. **Fork** the repository.  
2. **Create** a feature branch: `git checkout -b feature-name`  
3. **Commit** your changes: `git commit -m "Added a new feature"`  
4. **Push** and **Create a Pull Request** 🚀  

---

## 📝 License  
This project is open-source and available for modification and distribution.  

---

Made with ❤️ by **VAMSHI B**
