# Hotel Booking System - ANTI SEVEN

Welcome to the **ANTI SEVEN Hotel Booking System**, a simple console-based application for managing hotel room bookings, cancellations, and checkouts. This system is written in C# and provides an intuitive user interface for both customers and staff.

## Features

- **View All Rooms**: Check the status of all 10 hotel rooms (available or booked).
- **Book a Room**: Reserve a room by providing personal details and selecting the desired room type and duration.
- **Cancel a Booking**: Cancel an existing room reservation with password verification.
- **Check Out**: Process a room checkout, calculate the total price, and release the room for new bookings.
- **Predefined Room Details**:
  - Types: Luxury, Masterbed, Suite, Double, Single.
  - Prices: 1000 THB to 300 THB depending on the room type.

## Room Information

| Room No | Type       | Price (THB) |
|---------|------------|-------------|
| 1       | Luxury     | 1000        |
| 2       | Luxury     | 1000        |
| 3       | Double     | 500         |
| 4       | Masterbed  | 700         |
| 5       | Masterbed  | 700         |
| 6       | Suite      | 600         |
| 7       | Single     | 300         |
| 8       | Double     | 500         |
| 9       | Suite      | 600         |
| 10      | Single     | 300         |

## Getting Started

### Prerequisites

- .NET 5.0 or later installed on your machine.
- A code editor like Visual Studio, Visual Studio Code, or Rider.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Hotel-Booking-System-Anti-Seven.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Hotel-Booking-System-Anti-Seven
   ```
3. Open the project in your preferred IDE.

### Running the Application

1. Build the solution in your IDE.
2. Run the program.
3. Follow the prompts in the console to use the features.

## Usage

1. **Start the program** and choose from the menu:
   - View Rooms
   - Book a Room
   - Cancel Booking
   - Check Out
   - Exit
2. **Follow the prompts** to provide necessary details (e.g., room number, personal information).
3. Manage bookings and payments effortlessly.

## Code Highlights

- **Room Management**: An array structure (`rooms[]`) tracks room statuses.
- **Customer Information**: A 2D array (`userInfo[,]`) stores details like name, passport, and password.
- **Pricing**: Room prices are calculated based on type and the number of days booked.
- **Validation**: Input validation ensures reliable and secure data handling.

## Future Improvements

- Add a graphical user interface (GUI) for improved user experience.
- Enable room customization (e.g., number of beds, amenities).
- Add support for storing data in a database.

**Happy Booking!**
