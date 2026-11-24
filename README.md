# LibraryDesk: Library Inventory Management

A single-file web app (HTML, CSS, vanilla JavaScript, no dependencies) for managing a library's books, copies, loans, fines and members.

## Run
Open `index.html` in any browser. Data is held in memory (sample data is preloaded).

## Features
- **Catalog:** add books, search, multiple copies per title (duplicate ISBN adds copies), safe delete/remove
- **Circulation:** issue, return, renew once, mark lost, loan history
- **Rules:** max 3 books per member, no overdue items, fines under 100, one copy per title per member
- **Fines:** 2 per day late, 300 for lost books, pay or waive
- **Waitlist:** first-come, first-served queue; returned copies held for the next member
- **Insights:** demand score suggests which titles to buy more of; due-in-7-days chart; activity log
- **Demo control:** "Simulate +7 days" advances the clock to show overdue and fines

## Screenshots

### 1. Dashboard Overview
![Dashboard Overview](screenshots/01_dashboard.png)

### 2. Catalog & Search
![Catalog](screenshots/02_catalog.png)

### 3. Adding Book Copies
![Add Copies](screenshots/03_add_copies.png)

### 4. Safe Delete Protection
![Safe Delete](screenshots/04_delete_blocked.png)

### 5. Issue Book Flow
![Book Issue](screenshots/05_issue_ok.png)

### 6. Waitlist Queue
![Waitlist](screenshots/06_waitlist.png)

### 7. Member Borrowing Limits
![Limit Check](screenshots/07_limit_blocked.png)

### 8. Overdue & Late Return Simulation
![Late Return](screenshots/08_late_return.png)

### 9. Fines Management
![Fines](screenshots/09_fines.png)

### 10. Members Directory
![Members](screenshots/10_members.png)

### 11. Demand Insights & Analytics
![Insights](screenshots/11_dashboard_insights.png)

### 12. Full Circulation & Loan History
![Circulation](screenshots/12_circulation_full.png)

See the full write-up in `Q2_Library_Inventory_Management.pdf`.

## Future work
Date-based reservations, barcode scanning, reminders, persistent database, multiple branches, user roles.
