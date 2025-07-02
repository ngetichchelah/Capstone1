# Hiker Registration & Admin Payment Tracker 

### Project Description
This project is a hiking registration and admin tracking tool designed for adventure or hiking organizers. 
It allows hikers to register for an upcoming hike, stores their details in a file, and generates a PDF receipt for each registration. 
Admins can securely log in to manage registrations — view, edit, delete, and update payment status. 
It also includes simulated payment reminders and displays fun hiking facts on successful registration.
The system includes a Tkinter-based GUI and integrates an external weather API to show hike weather forecasts based on the hike date and location.

### Problem statement
Manual spreadsheets make it easy to lose track of partial payments and hiker contact details. This tool centralizes that workflow in one click-and-type desktop app.
This Tkinter-based GUI application aims to help register hikers, track their payment status, simulate reminders for pending payments, and analyze registrations using basic data analysis tools.

The goal is to build a real-world tool that uses file handling, GUI development, API integration, and data search/filtering — all essential programming concepts in one functional package.

### Planned Features
 * User input (e.g., name, contact, hike info)
 * Loops and conditionals
 * Functions and classes
 * File handling (.csv and .txt)
 * Simple GUI (Tkinter)
 * External API (weather forecast)
 * Score or data tracking (via Treeview admin dashboard)

### Technologies / Concepts I Plan to Use
* Python core (functions, loops, file I/O, conditionals)
* Tkinter and ttk (for GUI and Treeview)
* requests (for weather API integration)
* pandas (to read/write/search CSV files)
* fpdf (to generate registration receipts)
* threading (to simulate delayed reminders)
* datetime (for hike date logic and comparisons)

### Data Sources
 * API → OpenWeatherMap API (for hike weather conditions)
 *  Local files → hiker_data.csv, admins.csv, fun_facts.txt

### Success Criteria
The project is considered complete when:
- A user can register a hiker with name, contact, hike, and payment details.
- Data is saved to a CSV file.
- A PDF receipt is generated.
- Admins can log in and view/edit/delete records.
- Weather conditions are shown for hike date and location.
- The system simulates a reminder after 3 days for partial payments.
- Hike facts are randomly shown on each registration.

### Stretch Goals
- Export dashboard insights (e.g., top hikes, payment completion rate)
- Visualize hiker data with matplotlib
- Add SMS or email reminders using Twilio or SMTP
- Automatically scrape and refresh fun facts online
- Add user login system for hikers (to register/manage their bookings)
- Data visualization (planned future dashboard with matplotlib)
 
