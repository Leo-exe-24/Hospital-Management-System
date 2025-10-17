# Hospital Management System

## Project Summary  
The **Hospital Management System (HMS)** is a web-based application developed to streamline the day-to-day operations of hospitals and clinics. It facilitates management of patients, doctors, appointments, prescriptions, and payments through a unified and efficient platform.  
The system provides dedicated portals for **administrators**, **doctors**, and **patients**, each with specific functionalities to ensure smooth communication and coordination across the hospital network.

---

## Features

### Patient Module
- Patients can register and log in securely.  
- They can book appointments by selecting:
  - Type of doctor (e.g., General, Neurosurgeon, etc.)
  - Specific doctor from the available list.  
- The consulting fee is displayed automatically based on the chosen doctor.  
- Patients can choose a valid future date and time for the appointment.  
- A JavaScript alert confirms successful booking.  
- After the scheduled appointment time has passed, patients can pay the consultation fees and download a PDF receipt for their appointment.

### Doctor Module
- Doctors can log in using their credentials to view all upcoming appointments.  
- They can view patient details and prescribe medication after consultation.

### Admin/Reception Module
- Admin can view and manage all patient and doctor information.  
- Admin can add or delete doctor records directly from the interface.  
- Default admin credentials:
  - **Username:** admin  
  - **Password:** admin123  
- Admin can also access doctor login credentials from the admin dashboard to test or manage the doctor’s interface.

---

## Technology Stack

| Category | Technology |
|-----------|-------------|
| Frontend | HTML5, CSS3, JavaScript |
| Backend | PHP (Core PHP) |
| Database | MySQL |
| Styling | Custom CSS (style1.css, style2.css, assets/css/themes/) |
| Server | Apache (via XAMPP or WAMP) |

---

## Installation & Setup

### Prerequisites
Ensure you have the following installed:
- XAMPP or WAMP (with Apache and MySQL enabled)
- PHP 7.0 or higher

### Steps

1. **Clone or Download the Repository**  
   ```bash
   git clone [https://github.com/Leo-exe-24/Hospital-Management-System]
   ```

2. **Move the Project to Server Root**  
   - For XAMPP: `C:\xampp\htdocs\`  
   - For WAMP: `C:\wamp\www\`

3. **Import the Database**  
   - Start Apache and MySQL from your XAMPP/WAMP control panel.  
   - Open your browser and go to:  
     ```
     https://localhost/phpmyadmin/
     ```
   - Create a new database named `myhmsdb`.  
   - Import the file `myhmsdb.sql` located in the project folder.  
   - Once imported successfully, ensure all tables are visible in phpMyAdmin.

4. **Run the Application**  
   - Open your browser and go to:  
     ```
     http://localhost/Hospital-Management-System-master/index.php
     ```

---

## Folder Structure
```
Hospital-Management-System/
│
├── admin-panel.php
├── doctor-panel.php
├── index.php
├── func.php
├── myhmsdb.sql
├── assets/
│   ├── css/
│   └── images/
└── ...
```

---

## Future Improvements
- Role-based access control (RBAC) for enhanced security.  
- Migration to a modern PHP framework such as Laravel for scalability.  
- Integration of email and SMS notifications for appointment reminders.  
- Enhanced reporting and analytics for hospital operations.  

---

## Contributing
Contributions are welcome.  
To contribute:
1. Fork the repository.  
2. Create a new branch (`feature/your-feature`).  
3. Commit your changes.  
4. Submit a Pull Request with a clear description.

---

## License
This project is open source and distributed under the **MIT License**.

---

## Screenshots
*(Add your screenshots below to illustrate the application interfaces and workflows)*

- **Home Page:**  
  *(Screenshot Placeholder)*  

- **Admin Dashboard:**  
  *(Screenshot Placeholder)*  

- **Doctor Panel:**  
  *(Screenshot Placeholder)*  

- **Patient Booking Interface:**  
  *(Screenshot Placeholder)*  
