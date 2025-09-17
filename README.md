# ⚡ QuickBite

QuickBite is a food ordering platform built using Spring Boot for the backend, MySQL as the database, and **HTML/CSS/JavaScript (Thymeleaf) for the frontend.   
The system supports two main roles: Users and Admins.

---

## 🛠 Tech Stack

**Backend**
- Java 17+
- Spring Boot (Controllers, Services, Repositories)
- Maven (build tool)

**Database**
- MySQL (Relational Database)
- Spring Data JPA / Hibernate for ORM

**Frontend**
- HTML, CSS, JavaScript
- Thymeleaf (templating engine) integrated with Spring Boot

---

## 👥 User Roles

### 🧍 User
- Register and log in to their account
- Browse the food menu
- Add items to cart and place orders
- View order history and track status

---

### 🛡️ Admin
The **Admin** manages the entire system and has complete control over the platform.  
Admin tasks include:

- 📝 **Manage Menu Items**
  - Add new food items (name, price, category, description, image)
  - Update details of existing food items
  - Delete food items from the menu

- 📦 **Manage Orders**
  - View all user orders
  - Approve or reject pending orders
  - Update order status (e.g. preparing, dispatched, delivered)

- 👥 **Manage Users**
  - View all registered users
  - Block or delete suspicious accounts if needed

- 📊 **Monitor Platform Activity**
  - Track overall orders and sales data
  - Maintain data integrity and database records

The admin has access to a **secure admin dashboard** where all of these operations can be performed.

---

## 📋 Prerequisites

Install the following on your system:

- **Java JDK 17+** → [Download](https://adoptium.net)
- **MySQL Server** → [Download](https://dev.mysql.com/downloads/installer/)
- **VS Code / IntelliJ IDEA** (any Java IDE)
- **Extension Pack for Java** (if using VS Code)

---

## ⚙️ Setup Instructions

1. **Clone or Download the Project**
   ```bash
   git clone <repository-url>
   cd QuickBite

2.  **Configure MySQL Database**

Create a new database (e.g. quickbite)
Update the src/main/resources/application.properties file

3. **Run the Application**

.\mvnw.cmd spring-boot:run for windows

4. **Accessing the App**

Once the application starts, open your browser and go to:
http://localhost:8080







