# Library-Management-System

A robust, terminal-based Library Management System built to automate core library operations, including member registration, catalogue management, book issuing/returning, and automatic fine calculation.

---

## Features

* **Member Management**: Register, update, search, and manage member profiles and borrowing limits.
* **Book Inventory Management**: Catalogue books, track physical copies, search by author/title/category, and monitor real-time availability.
* **Issue & Return Workflow**: Process loans, track due dates, and dynamically compute late fines upon return.
* **Data Persistence**: Uses an embedded SQLite database via JDBC for reliable transactional data storage without external server dependencies.
* **Robust Quality Assurance**: Built-in exception handling, input validation, structured transaction logging, and unit tests using Jest.

---

## Tech Stack & Dependencies

* **Language**: Java / Node.js (TypeScript)
* **Database**: SQLite / PostgreSQL
* **Testing**: Jest (`jest`)
* **Build/Package Manager**: npm

---

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:
* Node.js (v18+)
* npm (v9+)

### Installation

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/your-username/library-management-system.git](https://github.com/your-username/library-management-system.git)
   cd library-management-system
