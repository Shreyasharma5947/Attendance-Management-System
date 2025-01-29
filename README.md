
# **Attendance Management System**  
*A JavaFX & MySQL-based attendance tracking system*  

## **📌 Project Overview**  
The **Attendance Management System** is a desktop application built using **JavaFX** for the UI and **MySQL** for the database. It allows administrators to record and manage student attendance efficiently.  

## **🔧 Features**  
✔️ **User Authentication:** Secure login system for Admins and Students  
✔️ **Role-Based Access:** Admin can manage attendance, students can only view  
✔️ **Attendance Entry:** Admins can add attendance records  
✔️ **Attendance Display:** Users can view and search attendance records  
✔️ **Database Integration:** Data is stored in a structured MySQL database  
✔️ **Interactive UI:** Built using JavaFX with FXML for a clean and modern look  

## **📂 Project Structure**  

```
📦 Attendance-Management-System  
 ┣ 📂 src  
 ┃ ┣ 📜 Atd_Mn_Sys.java       # Main class (entry point)  
 ┃ ┣ 📜 Attendance.java       # Database connection and attendance handling  
 ┃ ┣ 📜 InsertController.java # Manages attendance entry logic  
 ┃ ┣ 📜 DisplayController.java # Controls attendance display  
 ┃ ┣ 📜 LoginasController.java # Handles user login logic  
 ┃ ┣ 📂 fxml  
 ┃ ┃ ┣ 📜 Login.fxml         # Login screen UI  
 ┃ ┃ ┣ 📜 Loginas.fxml       # User type selection UI  
 ┃ ┃ ┣ 📜 Insert.fxml        # Attendance entry UI  
 ┃ ┃ ┣ 📜 Display.fxml       # Attendance display UI  
 ┃ ┣ 📂 assets  
 ┃ ┃ ┣ 📜 logo.png           # Project logo  
 ┣ 📂 database  
 ┃ ┣ 📜 attd_mng_sys.sql     # Database schema and sample data  
 ┣ 📜 README.md              # Project documentation  
 ┣ 📜 LICENSE                # License information  
```

## **🛠️ Technologies Used**  
- **JavaFX** - UI framework for Java applications  
- **FXML** - XML-based UI design  
- **MySQL** - Database for attendance storage  
- **JDBC** - Java Database Connectivity for MySQL  

## **🚀 How to Run the Project**  

### **Step 1: Clone the Repository**  
```sh
git clone https://github.com/Shreyasharma5947/Attendance-Management-System.git
cd Attendance-Management-System
```

### **Step 2: Setup the Database**  
1. Install **MySQL** and create a new database.  
2. Import the provided `attd_mng_sys.sql` file.  
3. Update database credentials in `Attendance.java` file.  

### **Step 3: Run the Application**  
1. Open the project in an IDE (**IntelliJ IDEA, Eclipse, NetBeans**).  
2. Ensure JavaFX libraries are properly configured.  
3. Run the `Atd_Mn_Sys.java` file.  

---



---

## **💡 Future Enhancements**  
🚀 Add **graphs and charts** for better data visualization  
📩 Implement **email notifications** for low attendance  
📱 Create a **mobile version** using JavaFX for Android  

## **📝 License**  
This project is licensed under the **MIT License** – you are free to modify and distribute it.  

---

