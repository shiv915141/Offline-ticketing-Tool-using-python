🎫 Ticket Management System

A simple desktop-based Ticket Management System built with Python, Tkinter, and Pandas.
The application allows users to create, update, view, and check the status of support tickets with data stored in a CSV file.
The project has been packaged as an .exe file for easy use without requiring Python installation.

🚀 Features

Add New Ticket
Create a new ticket by entering details such as Ticket ID, Query, Priority, Acknowledgement, Current Status, and Resolved status.

Update Ticket
Modify details of an existing ticket using its Ticket ID. Updates are saved in the CSV file.

View Current Tickets
Display a list of all tickets stored in the system.

Check Ticket Status
Retrieve and display ticket details by entering the Ticket ID.

Data Persistence
All tickets are stored in a tickets.csv file, ensuring data remains available across sessions.

🖥️ GUI Layout

Ticket ID field (numeric only)

Query field (short description of the issue)

Priority field (e.g., High, Medium, Low)

Acknowledgement field (extra notes)

Current Status field (e.g., Pending, In Progress, Resolved)

Resolved checkbox (mark ticket as resolved)

Buttons:

Add Ticket → Adds a new ticket

Update Ticket → Updates an existing ticket

Current Tickets → Shows all tickets

Check Status → Shows details of a specific ticket

📦 Installation & Setup
1. Running the .exe file

Download the TicketSystem.exe file.

Double-click to launch the program.

No Python installation is required.

2. Running from Source (Python file)

If you prefer to run the project as a Python script:

# Clone or download the repository
git clone <(https://github.com/shiv915141/Offline-ticketing-Tool-using-python)>
cd TicketSystem

# Install dependencies
pip install pandas tk


Run the app:

python ticket_system.py

📂 Project Files


tickets.csv → Data file storing ticket information

TicketSystem.exe → Packaged executable version (for Windows)

README.md → Project documentation

⚙️ Tech Stack

Python – Core logic

Tkinter – GUI framework

Pandas – Data handling & CSV storage


📝 Notes

Make sure tickets.csv exists in the same directory as the .exe. If it doesn’t, the program will create one automatically after adding the first ticket.

Always use unique numeric Ticket IDs when creating tickets.

👉 This project is like a mini helpdesk tool where tickets can be logged, tracked, and updated.
