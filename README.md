# Hiker Registration & Payment Tracker
H.R.P.T

A beginner-friendly Python project for outdoor brands and adventure organizers. 
Manual spreadsheets make it easy to lose track of partial payments and hiker contact details. This tool centralizes that workflow in one click-and-type desktop app.
This Tkinter-based GUI application aims to help register hikers, track their payment status, simulate reminders for pending payments, and analyze registrations using basic data analysis tools.

## 🌟 Features

*  Hiker Registration: Collects name, contact (phone/email), hike name, and payment status.
*  Reminder Simulation: Partial payments trigger a simulated reminder 3 days later.
*  Fun Facts: Each registration shows a random hiking fun fact (from a .txt file).
*  Export to Excel: All hiker data can be saved to an Excel file.
*  Search: Find hikers by name or contact.
*  Mark Payments Complete: Admin can update partial payments.
*  Incorporate hiking fun facts that appear randomly after registration.


## 🔄 How It Works

* Admin enters hiker details (name, contact, hike, payment).
* Upon submission:

  * Data is stored in a CSV file.
  * A hiking fun fact is shown.
  * If partial payment: simulated reminder is scheduled.

* Admin options:
  * View reminders
  * Mark payment complete
  * Export to Excel
  * View calendar or dashboard
  * Search hikers by name/contact


