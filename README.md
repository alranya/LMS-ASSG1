# 📚 Havad Engineering College Library Management System (LMS)

A comprehensive, multi-page Library Management System designed specifically for engineering colleges and universities. This project is built using **pure HTML** with clean table layouts and semantic form controls, requiring **no CSS or external styling frameworks**.

---

## 🚀 Project Overview & Pages

The application consists of **5 core pages** that simulate a complete academic library workflow for students, faculty, and administrators:

1. **`login page.html` (Secure Portal Entry)**
   - Features a classic two-column split layout with a welcoming engineering library illustration on the left and login credentials on the right.
   - Includes role selection options for Students, Faculty Members, and Librarians/Admins.

2. **`signup page.html` (New Member Registration)**
   - Allows new users to register their institutional credentials.
   - Tailored specifically for engineering programs with dropdowns for Departments (ECE, CSE, EEE, Mechanical, Civil) and Academic Semesters.

3. **`dashboard.html` (Personal Member Account)**
   - Serves as the user's home base after logging in.
   - Displays profile details, currently issued books with due dates, fine tracking status, and an integrated book purchase request form.

4. **`view book.html` (Catalog & Search Inventory)**
   - Public-facing inventory directory where users can search for textbooks by keyword and filter by engineering branch.
   - Uses structured data tables to display availability and reservation options.

5. **`add book.html` (Admin Inventory Management)**
   - Restricted dashboard for librarians and administrators to stock new books into the database.
   - Includes input fields for titles, authors, ISBN/accession numbers, target branches, and copy counts.

---

## 🛠️ Tech Stack & Architecture
* **Core Technology:** HTML5 (Semantic tags, tables, forms, frames/links)


---

## 📂 File Directory Structure

Ensure all files are placed together in the exact same root directory to keep relative hyperlinks functional:

```text
library-management-system/
├── login page.html
├── signup page.html
├── dashboard.html
├── view book.html
└── add book.html
```

---

## 💻 How to Run Locally

1. Download or clone this repository to your local computer.
2. Verify that all 5 `.html` files reside in the same folder.
3. Double-click **`login page.html`** to launch the portal in any modern web browser.
4. Seamlessly navigate across pages using the built-in links and form buttons!

---

## 📄 License
This project is open-source and available for educational and portfolio purposes.

