# meeting_room_booking
A Python-based console application for booking meeting rooms with user authentication, booking management, and email notifications. This project demonstrates secure password handling, file-based data storage, and basic email integration.

## Features

- **User Management:**
  - Sign up and log in functionality.
  - Password reset with email OTP verification.
  - Secure password storage using bcrypt hashing.

- **Room Booking:**
  - Create, read, update, and delete bookings for meeting rooms.
  - Check for room availability to prevent booking conflicts.
  - Save bookings to a JSON file for persistence.

- **Email Notifications:**
  - Send booking confirmation and update emails.
  - Uses SMTP for sending emails.

- **Console Interface:**
  - Simple and interactive menu-driven interface.
  - Colored text for different types of messages.

## Getting Started

### Prerequisites

- Python 3.x
- Required Python libraries: `datetime`, `json`, `os`, `smtplib`, `getpass`, `email`, `bcrypt`, `re`

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/meeting-room-booking-system.git
    cd meeting-room-booking-system
    ```

2. Install the required Python libraries:
    ```sh
    pip install bcrypt
    ```

### Usage

1. Run the main script:
    ```sh
    python meeting_room_booking.py
    ```

2. Follow the on-screen prompts to sign up, log in, and manage bookings.

### Configuration

- Email credentials and server details need to be configured in the `send_email` method:
    ```python
    sender_email = "your_email@gmail.com"
    sender_password = "your_email_password"
    smtp_server = 'smtp.gmail.com'
    smtp_port = 587
    ```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.

