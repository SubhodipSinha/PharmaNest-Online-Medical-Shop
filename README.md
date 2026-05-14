# PharmaNest: Online Medical Shop Application 💊

A comprehensive e-commerce platform designed to facilitate secure browsing, inventory management, and real-time processing for pharmaceutical products. Built using a robust Java EE architecture to ensure highly optimized server-side processing and seamless database transactions.

## 🛠️ Tech Stack & Architecture
* **Frontend:** HTML5, CSS3, JavaScript (ES6), jQuery, AJAX
* **Backend:** Core Java, Servlets, JSP (JavaServer Pages)
* **Database:** Oracle SQL (Relational Database Management System)
* **Data Interchange:** JSON, RESTful Service Communication

## 📌 Core System Features
* **Secure Authentication:** Role-based access control for standard Customers and System Administrators.
* **Dynamic Inventory Management:** Real-time tracking of medication stock levels, categories, and pricing.
* **Asynchronous Processing:** AJAX-driven search and cart operations utilizing JSON data interchange to prevent full-page reloads.
* **Optimized Persistence:** Custom JDBC connection pooling and prepared statements for secure, high-performance Oracle database transactions.

## ⚙️ System Workflow
1. **Client Tier:** Captures user actions via responsive HTML/CSS UI; triggers asynchronous requests via jQuery/AJAX.
2. **Web Tier:** Java Servlets intercept requests, execute core business logic, and manage session states.
3. **Presentation Tier:** JSP dynamically renders server responses and integrated catalog data back to the client.
4. **Data Tier:** Direct, secure interaction with the Oracle database schema ensuring strict ACID compliance.

---
*Status: Active Development*
