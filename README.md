
# Patient Management System

A lightweight, CSV-based desktop application to manage patient data, user login, and visit records. This system is ideal for small clinics or individual practitioners.

## 📦 Project Structure

```
├── Login.py                # Handles user login/authentication
├── Patient_final.py        # Manages patient information
├── PatientVisit.py         # Manages visit/appointment data
├── sdpq.py                 # Supporting logic or interface
├── sdpx_final.py           # Possibly the main entry point
├── SDP_APP.bat.txt         # Batch file to run the application on Windows
├── user_records.csv        # Stores login credentials
├── patient_records.csv     # Stores patient details
├── visit_records.csv       # Stores visit/appointment history
```

## 🚀 How to Run

1. Ensure you have **Python 3.x** installed.
2. Clone or download this repository.
3. Navigate to the project folder in the terminal.
4. Run the main script:

```bash
python sdpx_final.py
```

Alternatively, use the Windows batch file:

```bash
Double-click on SDP_APP.bat.txt (rename to .bat if needed)
```

## 🧑‍⚕️ Features

- User authentication with CSV-based login
- Add, update, and view patient details
- Record and view patient visit history
- Simple GUI interface using Tkinter

## 🗃️ Data Storage

Data is stored in local `.csv` files:
- `user_records.csv`: Username and password information
- `patient_records.csv`: Patient ID, name, age, gender, etc.
- `visit_records.csv`: Visit date, reason, and related patient ID

## 📌 Requirements

- Python 3.x
- Standard Python libraries (no external dependencies):
  - `tkinter`
  - `csv`
  - `os`
  - `datetime`

## 🛠️ Setup Notes

If any `.csv` files are missing, the application will create them automatically on first run.

## ✍️ Author

- Developed as part of a Student Development Project (SDP)
- Date: June 2024

## 📄 License

This project is for educational purposes only.
