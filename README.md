# HiltonHotel
This is a group project developed by  CS students to implement JavaFX code for Hilton Hotel Booking System
# Hotel Booking System

A comprehensive desktop application for managing hotel bookings, built with Java and JavaFX. This system allows users to browse rooms, make reservations, and manage their bookings, while providing administrators with tools to manage rooms, users, and system settings.

## 🚀 Features

### For Guests (Users)
*   **User Authentication:** Secure login and registration system.
*   **Room Browsing:** View available rooms with details (type, price, amenities).
*   **Booking Management:** Make new reservations and view booking history.
*   **Profile Management:** Update personal information and view account balance.
*   **Notifications:** Receive updates about booking status.

### For Administrators
*   **Dashboard:** Overview of hotel statistics and recent activities.
*   **Room Management:** Add, update, or remove rooms from the system.
*   **Booking Oversight:** View and manage all guest reservations.
*   **User Management:** View registered users.

## 🛠️ Technologies Used

*   **Language:** Java 21
*   **GUI Framework:** JavaFX 21
*   **Database:** SQLite (File-based, no server setup required)
*   **Build Tool:** Maven
*   **Security:** BCrypt for password hashing
*   **Icons:** Ikonli (FontAwesome)

## 📋 Prerequisites

Before running the application, ensure you have the following installed:

*   **Java Development Kit (JDK) 21** or higher.
*   **Maven** (for building the project).

## ⚙️ Setup and Installation

1.  **Clone or Download** the project repository.
2.  **Navigate** to the project root directory in your terminal or command prompt:
    ```bash
    cd path/to/HotelBokingSystem
    ```

3.  **Build the project** using Maven. This will download all necessary dependencies (JavaFX, SQLite driver, etc.) and compile the code:
    ```bash
    mvn clean package
    ```

## ▶️ How to Run

After building the project successfully, you can run the application using the generated executable JAR file:

```bash
java -jar target/hotel-booking-system-1.0.0.jar
```

### Default Login Credentials

The system creates default users the first time it runs:

*   **Admin Account:**
    *   Email: `admin@hotel.com`
    *   Password: `system`

*   **User Account:**
    *   Email: `john@example.com`
    *   Password: `system`

## 🗄️ Database

The application uses **SQLite**.
*   A file named `hotel.db` will be automatically created in the project root directory upon the first launch.
*   No manual database configuration or server startup is required.

## 📂 Project Structure

*   `src/main/java`: Source code
    *   `application`: Main entry point (`Launcher.java`, `Main.java`)
    *   `controller`: JavaFX controllers for handling UI logic
    *   `dao`: Data Access Objects for database interactions
    *   `model`: Data models (POJOs)
    *   `util`: Utility classes (Database connection, etc.)
*   `src/main/resources`: Non-code assets
    *   `view`: FXML files for the UI layout
    *   `css`: Stylesheets
    *   `images`: Application images and icons

## 🤝 Contributing

1.  Fork the repository
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request
