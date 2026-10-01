# TripHalt - Hotel Search and Booking Website

## 📌 Overview
TripHalt is a hotel search and booking website built using **JSP (JavaServer Pages)**. It allows users to search for hotels, view details, and make bookings seamlessly. The platform provides an interactive user experience with secure payment integration and efficient hotel management.

## 🚀 Features
- 🔍 **Hotel Search:** Search hotels based on location, price range, and ratings.
- 🏨 **Hotel Details:** View hotel information, including images, amenities, and customer reviews.
- 🛎️ **Booking System:** Users can book hotels with an intuitive reservation system.
- 👤 **User Authentication:** Secure login and signup system for users.
- 💳 **Payment Integration:** Supports online payments for confirmed bookings.
- 🛠 **Admin Dashboard:** Admin can manage hotel listings, bookings, and user accounts.
- ⭐ **Reviews & Ratings:** Users can review and rate hotels based on their experience.

## 🏗 Tech Stack
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Backend:** JSP, Servlets, JDBC
- **Database:** MySQL
- **Server:** Apache Tomcat

## 📂 Project Structure
```
TripHalt/
│-- src/
│   ├── controllers/        # Servlet controllers
│   ├── models/             # Database models
│   ├── views/              # JSP pages
│-- web/
│   ├── assets/             # CSS, JS, Images
│   ├── WEB-INF/            # Configuration files
│-- database/               # SQL scripts
│-- README.md               # Project documentation
```

## ⚙️ Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/TripHalt.git
   ```
2. Import the project into **Eclipse IDE** or any Java IDE supporting JSP.
3. Set up the **MySQL database**:
   - Create a database named `triphalt_db`.
   - Run the SQL script from the `database/` folder to set up tables.
4. Configure database credentials in `dbConfig.jsp`:
   ```jsp
   <%! String DB_URL = "jdbc:mysql://localhost:3306/triphalt_db";
       String DB_USER = "root";
       String DB_PASS = "yourpassword";
   %>
   ```
5. Deploy the project on **Apache Tomcat** and start the server.
6. Open your browser and go to:
   ```
   http://localhost:8080/TripHalt
   ```

## 🎯 Future Enhancements
- 🏷 Coupon system for discounts
- 📍 Google Maps API for hotel locations
- 📱 Mobile-friendly responsive UI

## 📝 License
This project is licensed under the **MIT License**.

---
🔹 Developed by **Nikhil**
