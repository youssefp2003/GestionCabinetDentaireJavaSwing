---

# 🦷 **Dental Clinic Management System**

A comprehensive Java-based desktop application designed to simplify dental clinic operations. Manage patient records, appointments, and user authentication efficiently with an intuitive interface and robust backend.

---

## ✨ **Features**

### **Actors in the System**
The application supports two key actors:
1. **Receptionist**:
   - Manages patient profiles, appointments, and balances.
   - Handles scheduling and patient communications.
2. **Dentist**:
   - Accesses detailed patient records, including medical histories and X-ray data.
   - Reviews and updates appointment treatments and notes.

### **Patient Management**
- Add, update, and retrieve detailed patient records.
- Store medical histories, contact information, and other essential data.
- Maintain a clean and organized patient database.

### **Appointment Scheduling**
- Calendar-based system for intuitive appointment management.
- Easily book, edit, or cancel appointments with a few clicks.
- Send automated email notifications for appointment confirmations or changes.

### **Secure User Authentication**
- Role-based login system ensures secure access for Receptionists and Dentists.
- Protect sensitive patient information and clinic records.

### **Interactive User Interface**
- Designed with **FlatLaf Look and Feel** for a modern, responsive UI.
- Modular design for seamless navigation between features.

### **Additional Functionalities**
- Track unpaid balances and generate summaries.
- Integrated email reminders to improve patient engagement.

---

## 🚀 **Technologies Utilized**

- **Programming Language**: Java 11+  
- **UI Framework**: Java Swing with FlatLaf for a polished appearance.  
- **Database**: SQLite for lightweight and reliable storage.  
- **Build Tool**: Maven for dependency management and project building.  
- **Email Integration**: JavaMail API for sending notifications.  
- **Scheduling**: JCalendar for calendar-based features.  

---

## 📂 **Directory Structure**

```plaintext
gestioncabinetdentairejavaswing/
├── README.md                     # Project documentation
├── dental_clinic.db              # SQLite database file
├── pom.xml                       # Maven configuration file
└── src/
    └── main/
        └── java/
            └── com/
                └── dentalclinic/
                    ├── DentalClinicApplication.java  # Main application entry point
                    ├── model/
                    │   ├── Appointment.java          # Appointment model class
                    │   └── Patient.java              # Patient model class
                    ├── ui/
                    │   ├── AppointmentPanel.java     # Panel for managing appointments
                    │   ├── CalendarPanel.java        # Calendar view for appointments
                    │   ├── LoginDialog.java          # Login dialog for secure access
                    │   ├── MainFrame.java            # Main application frame
                    │   ├── PatientRecordsPanel.java  # Panel for viewing patient records
                    │   └── PatientsPanel.java        # Panel for managing patients
                    └── util/
                        └── DatabaseUtil.java         # Utility class for database operations
```

---

## 📦 **Installation Guide**

### **Prerequisites**
- **Java Development Kit (JDK)**: Version 11 or higher.
- **Maven**: Version 3.x or later.
- **SQLite**: Ensure SQLite is installed or use the provided database file (`dental_clinic.db`).

### **Setup Instructions**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/youssefp2003/GestionCabinetDentaireJavaSwing.git
   cd gestioncabinetdentairejavaswing
   ```

2. **Build the Project**:
   Use Maven to install dependencies and compile the application:
   ```bash
   mvn clean install
   ```

3. **Run the Application**:
   Start the application using Maven:
   ```bash
   java -jar target/dental-clinic-management-1.0-SNAPSHOT.jar
   ```

4. **Access the Application**:
   - Login using credentials set for **Receptionist** or **Dentist**.
   - Begin managing patients, appointments, and clinic operations.

---

## 🗄️ **Database Schema**

### **Patients Table**
Stores detailed patient information, including:
- **ID**: Unique identifier for each patient.
- **Name**: Full name.
- **Contact Info**: Phone and email.
- **Medical History**: Notes on treatments and conditions.

### **Appointments Table**
Tracks all appointments with:
- **ID**: Unique identifier.
- **Patient ID**: Associated patient.
- **Date/Time**: Appointment schedule.
- **Description**: Treatment or consultation details.

---

## 🤝 **Contributing**

Contributions are welcome! Follow these steps to contribute:

1. **Fork the Repository**.
2. **Create a Feature Branch**:
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Commit Your Changes**:
   ```bash
   git commit -m "Add YourFeatureName"
   ```
4. **Push to Your Branch**:
   ```bash
   git push origin feature/YourFeatureName
   ```
5. **Open a Pull Request**.

---

## 📜 **License**

This project is licensed under the **MIT License**. See the `LICENSE` file for full details.

---

## 👤 **Author**
- **Youssef Abdelmoumene** – [GitHub Profile](https://github.com/youssefp2003)

--- 
