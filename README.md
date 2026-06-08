# School Management System

A **Python-based School Management System** that allows you to manage students, attendance, marks, results, fees, notices, and more through a simple command-line interface. Data is stored locally using **JSON**, making it lightweight and easy to use.

## Features

- Secure PIN-based login
- Auto-generated Student IDs
- Add, View, Update, and Delete students
- Class and Section management
- Global and class-wise subjects
- Subject-wise marks management
- Automatic calculation of:
  - Total Marks
  - Average
  - Percentage
  - Grade
  - Pass/Fail Status
- Daily attendance management
- Bulk attendance marking
- Attendance history and editing
- Low attendance alerts
- Sorting and filtering of students
- Result report generation
- Fee structure and payment management
- Class timetable management
- Notice board system
- Student ID card generation
- Import/Export data (CSV & JSON)
- Analytics and reports

---

## Technologies Used

- Python
- JSON
- CSV
- File Handling
- Hashlib (PIN security)
- UUID
- Datetime

---

## Project Structure

```
School-Management-System/
│
├── Student Management program.ipynb
├── school_data.json
└── README.md
```

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/school-management-system.git
```

2. Navigate to the project folder:

```bash
cd school-management-system
```

3. Open the notebook:

```bash
jupyter notebook
```

or run it inside VS Code.

---

## Data Storage

The application stores all information locally in:

- `school_data.json`

This includes:

- Student records
- Attendance
- Subjects
- Results
- Fees
- Timetable
- Notices

---

## Learning Concepts Covered

This project demonstrates:

- Python functions
- Dictionaries and lists
- File handling
- JSON operations
- Modular programming
- CRUD operations
- Data validation
- Report generation
- Basic security using hashing

---

## Future Improvements

- GUI using Tkinter or PyQt
- Web version using Flask/Django
- SQL database integration
- User roles (Admin/Teacher/Student)
- Email/SMS notifications
- Dashboard with charts
- Cloud deployment

---

## Author

**Depesh Kumar**

Aspiring AI Engineer | Python Developer | Building projects to strengthen programming and software development skills.
