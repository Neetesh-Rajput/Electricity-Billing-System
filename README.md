# Electricity Billing System

**A Java-based Electricity Billing System** that helps manage customer records, generate bills, and handle payments efficiently.  
It uses **Swing** for GUI and **MySQL** database for backend.

## Features
- Add / Edit / Delete customer records
- Generate monthly electricity bills
- View payment history
- Search customer by meter number or name
- Export bills / print (if implemented)

## Technologies Used
- Java (Swing, AWT)
- MySQL Database
- JDBC

## Project Structure
```
electricity-billing-system/
├─ src/                # Java source files
│   └─ electricity/billing/system/
├─ ebs.sql             # Database export file
├─ manifest.mf         # optional
├─ README.md
```

## How to Run
1. Download this repository or clone using Git:  
   ```
   git clone https://github.com/<your-username>/electricity-billing-system.git
   ```
2. Open the project in NetBeans: `File → Open Project → select folder`.
3. Import `ebs.sql` in MySQL to create the database and tables.
4. Update DB credentials in code if needed (`username` / `password`).
5. Run `Main.java` (or entry point class) to start the application.

## Notes
- Do **not** commit real DB passwords.  

## Author
Neetesh Rajput

