# Library Management & Banking System

A Python desktop application for managing library operations, member accounts, book inventories, and late fee transactions via an embedded mock banking system.

## Features

- **Book Inventory Management:** Add, edit, search, and delete book entries with strict ISBN validation and copy tracking.
- **Member System:** Auto-generate unique 6-digit Member IDs with collision checking, handle member searches, and restrict deletion until borrowed books and fines are resolved.
- **Borrowing & Returns:** Track 2-week loan windows, prevent double-borrowing of single titles, and automatically calculate daily late return fines.
- **Tobo Bank Integration:** Embedded mock banking module featuring user account registration, password complexity validation, deposit handling, and automated fine payments.
- **Data Persistence:** Lightweight flat-file storage using native Python CSV and text handling—no external database setup required.

## Tech Stack

- **Language:** Python 3
- **GUI Framework:** Tkinter (Standard Python Library)
- **Data Persistence:** CSV, Plain Text (`csv`, `os`, `datetime` modules)

## How to Run

1. Make sure you have **Python 3** installed.
2. Run the script directly from your terminal or IDE:
   ```bash
   python library_system.py
