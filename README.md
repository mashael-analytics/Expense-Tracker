# Expense Tracker

A simple and efficient Expense Tracking application using Python and SQLite, designed to run smoothly in Google Colab with database stored on Google Drive.

---

## Skills & Technologies Used

- **SQL (SQLite):**  
  - Database design and schema creation  
  - Table relationships and foreign keys  
  - Data insertion, querying, updating, and deletion  
  - Preventing duplicates using constraints and query logic  
  - Aggregate functions (`SUM`, `GROUP BY`) for reports  
  - Date filtering and sorting  
- **Python:**  
  - SQLite3 module for database operations  
  - File handling for export (CSV)  
  - Exception handling and validation  
- **Google Colab & Drive:**  
  - Mounting and working with Google Drive files  
  - Persistent database storage  
  - File download functionality  

---

## Features

- Add, list, and manage expense categories
- Add expenses with amount, category, description, and date
- Prevent duplicate expense entries for the same day
- Show detailed expense history
- Calculate total expenses
- Export expenses to CSV
- Filter expenses by date range
- Expense summary by category
- Save the database persistently in Google Drive
- Download database file locally for backup or analysis

---

## Getting Started

### Prerequisites

- Python 3.x
- Google Colab account
- Google Drive access (to store the database file)

---

### Setup Instructions

1. **Mount Google Drive**  
   Run the following code in Google Colab to access your Drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
