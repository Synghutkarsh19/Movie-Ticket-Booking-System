# Movie Ticket Booking System

This project is a Movie Ticket Booking System developed using Java Spring Boot API and MySQL database. It provides a web-based interface for users to browse available movies, select showtimes, and book tickets online. The system allows users to register, log in, and make secure payments for their bookings.

## Features

- User Registration: Users can create new accounts by providing their details.
- User Authentication: Registered users can log in to their accounts securely.
- Movie Listings: Users can view the list of available movies and their showtimes.
- Seat Selection: Users can select their desired seats for a particular showtime.
- Ticket Booking: Users can book tickets by providing necessary information and making payment.
- Payment Gateway Integration: Secure payment processing is integrated into the system.
- Booking History: Users can view their booking history and ticket details.
- Admin Panel: An admin panel is provided for managing movies, showtimes, and bookings.

## Prerequisites

- Java JDK 11 or higher installed
- Maven build tool
- MySQL database server
- IDE (e.g., IntelliJ, Eclipse)

## Setup Instructions

1. Clone the repository to your local machine:

2. Open the project in your IDE.

3. Update the MySQL database configuration in `application.properties` file located in the `src/main/resources` directory:
spring.datasource.url=jdbc:mysql://localhost:3306/movie_booking
spring.datasource.username=your-username
spring.datasource.password=your-password

4. Build and run the application using Maven:


5. The application should now be running on `http://localhost:8080`.

6. Open your web browser and navigate to `http://localhost:8080` to access the Movie Ticket Booking System.

## Usage

- Open the application in your web browser.
- If you are a new user, click on the "Register" link to create an account.
- If you are a registered user, click on the "Login" link to sign in.
- Browse the available movies and select a showtime.
- Choose your desired seats and proceed to the booking page.
- Provide the required information and make the payment.
- After successful booking, you will receive a confirmation with the ticket details.
- You can view your booking history by clicking on the "My Bookings" link.

## Admin Panel

- The admin panel can be accessed at `http://localhost:8080/admin` after logging in with the admin credentials.
- In the admin panel, you can manage movies, showtimes, and bookings.
- You can add new movies, update existing movies, and delete movies from the system.
- Showtimes for movies can be added, edited, and deleted.
- The admin panel also provides a view of all bookings with the ability to search and filter.

## Technologies Used

- Java Spring Boot: Provides the framework for building the API.
- MySQL: Used as the database to store movie, showtime, and booking data.
- Spring Data JPA: Simplifies database operations and ORM mapping.
- Thymeleaf: Server-side templating engine for rendering dynamic web pages.
- Bootstrap: CSS framework for responsive and visually appealing UI.
- Maven: Build tool for managing dependencies and building the project.

## Contributing

Contributions are welcome! If you have any ideas or improvements for the project, please create a pull request or open an issue.

## License

This project is licensed under the [MIT License](LICENSE).


