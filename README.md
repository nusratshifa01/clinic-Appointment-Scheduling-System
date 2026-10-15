# 🏥 Clinic Appointment Scheduling System

A C-based console application designed to manage patient registration, doctor information, and clinic appointments in a simple and organized way.

---

## 📌 Project Overview

The Clinic Appointment Scheduling System is an academic project developed using the C programming language. It helps clinic staff manage patient records, book appointments, view appointment schedules, search patient information, and cancel appointments.

The system uses file handling to store patient and appointment records locally, so the data can be loaded again when the program restarts.

---

## 🎯 Project Objectives

- Simplify clinic appointment scheduling.
- Maintain organized patient records.
- Display doctor information and consultation fees.
- Prevent double-booking of the same doctor at the same date and time.
- Store and retrieve records using file handling.
- Apply C programming concepts to a real-world problem.

---

## 🚀 Key Features

- **Patient Registration:** Register patients with unique IDs, names, ages, and phone numbers.
- **Doctor Information:** View doctor IDs, names, departments, and consultation fees.
- **Appointment Booking:** Schedule appointments for registered patients.
- **Conflict Detection:** Prevent double-booking of a doctor at the same date and time.
- **View Appointments:** Display all appointment records and their status.
- **Patient Search:** Search patient details and appointment history using a patient ID.
- **Appointment Cancellation:** Cancel an existing appointment using its appointment ID.
- **File Handling:** Save and load patient and appointment records using text files.
- **Input Validation:** Validate basic patient information and date and time formats.

---

## 🛠️ Tech Stack & Tools

- **Language:** C (C99 or higher)
- **Compiler:** GCC / MinGW
- **IDE:** Code::Blocks
- **Storage:** C File Handling
- **Version Control:** Git and GitHub

---

## 📂 Project Structure

```text
ClinicAppointmentSystem/
│
├── main.c
├── README.md
├── patients.txt
└── appointments.txt
```

- `main.c` — Main C source code.
- `README.md` — Project documentation.
- `patients.txt` — Stores patient records.
- `appointments.txt` — Stores appointment records.

*Note: The text files are generated automatically when records are saved.*

---

## 📋 Main Menu

1. Register New Patient
2. View Doctor List
3. Book Appointment
4. View All Appointments
5. Search Patient Appointments
6. Cancel Appointment
0. Exit

---

## ⚙️ How to Run the Project

### Using Code::Blocks

1. Install Code::Blocks with a C compiler.
2. Create a C Console Application.
3. Copy the source code into `main.c`.
4. Save the project.
5. Click **Build and Run** or press `F9`.
6. Follow the instructions displayed in the console.

### Using GCC

Compile the program:

```bash
gcc -std=c99 -Wall -Wextra main.c -o clinic
```

Run on Windows:

```bash
clinic.exe
```

Run on Linux or macOS:

```bash
./clinic
```

---

## 💡 C Programming Concepts Used

- Structures
- Arrays
- Functions
- Pointers
- Loops
- Conditional Statements
- String Handling
- File Handling

---

## ✅ Advantages

- Reduces manual record-keeping.
- Organizes patient and appointment information.
- Makes appointment searching easier.
- Helps prevent scheduling conflicts.
- Provides practical experience with C programming.

---

## ⚠️ Limitations

- Console-based user interface.
- Uses local text files instead of a database.
- No login or authentication system.
- Does not validate every calendar rule or prevent past-date bookings.
- Designed for educational purposes, not production medical use.

---

## 🔮 Future Improvements

- Integrate a MySQL database.
- Add administrator login functionality.
- Manage doctor availability and clinic working hours.
- Add appointment reminders.
- Develop a graphical user interface.
- Generate daily and monthly reports.

---

## 👥 Team Information

- **Project Name:** Clinic Appointment Scheduling System
- **Programming Language:** C
- **Project Type:** Academic Project
- **Team Name:** [NOVA CORE]

### Collaborators

- [Sifa Akter] — Team Leader
- [Zannatul Mowya Iramoni] — Team Member
- [Shah Tasnim Abid] — Team Member
- [MD Rakibul Islam] — Team Member
- [Shorna Islam] — Team Member

### Project Supervisor

- **Teacher:** [Mehedi Hasan Faysal]
- **Course:** [Capstone Project]

---

## 🏁 Conclusion

The Clinic Appointment Scheduling System demonstrates how C programming can be used to solve a practical problem in clinic management. It provides basic patient registration, doctor information, appointment booking, searching, cancellation, and file-based record management.

This project helps students understand structured programming, data management, file handling, and problem-solving.

---

**Developed as an academic project using C programming.**
