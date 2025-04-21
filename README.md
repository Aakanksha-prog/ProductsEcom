# 🛒 ProductsEcom

A simple backend application for managing products in an e-commerce platform. Built using **Java**, **Spring Boot**, and **JPA**, this project serves as a foundation for product-related operations such as adding, updating, retrieving, and deleting products.

---

## 🚀 Features

- Add new products
- View all products
- Get product by ID
- Update existing product details
- Delete a product
- Basic validation and exception handling
- Uses H2 or MySQL (configurable) as the database

---

## 🧰 Tech Stack

- **Java 17**
- **Spring Boot**
- **Spring Data JPA**
- **Maven**
- **MySQL / H2 Database**
- **Lombok**

---

## 📁 Project Structure

ProductsEcom/ ├── src/ │ ├── main/ │ │ ├── java/ │ │ │ └── com.example.productsecom/ │ │ │ ├── controller/ │ │ │ ├── model/ │ │ │ ├── repository/ │ │ │ └── service/ │ │ └── resources/ │ │ ├── application.properties │ │ └── data.sql ├── pom.xml

yaml
Copy
Edit

---

## 🛠️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Aakanksha-prog/ProductsEcom.git
   cd ProductsEcom
Open in your IDE (e.g., IntelliJ IDEA, Eclipse)

Build the project

bash
Copy
Edit
./mvnw clean install
Run the application

bash
Copy
Edit
./mvnw spring-boot:run
Access API

Swagger (if configured): http://localhost:8080/swagger-ui.html

H2 Console (if using H2): http://localhost:8080/h2-console

🧪 Sample SQL
Add this to data.sql to pre-load data:

INSERT INTO product (name, description, brand, price, category, release_date, available, quantity)
VALUES ('Tata Nexon', 'A compact SUV with excellent safety features.', 'Tata Motors', 750000.00, 'Cars', '2024-01-15', true, 50);
✍️ Author
Aakanksha — GitHub
