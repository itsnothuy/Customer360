# Customer360 - Django Application

## Project Overview

Customer360 is a simple Django-based application developed for managing customer communication records. The application consolidates various communication channels into a central platform, allowing users to capture, store, and view recent interactions with customers. This project focuses on storing communication details such as the channel, communication direction, and a summary of the interaction.

The system is designed to meet the following requirements:
1. Capture and store communication records.
2. Display interactions from the last 30 days.
3. Provide a professional customer communication management system.

## Objectives

1. **Develop a screen to capture communication records**:
   - A form that captures key information such as:
     - Channel (Email, Phone, Chat, etc.)
     - Direction (Inbound or Outbound)
     - Summary of the interaction

2. **Display recent interactions**:
   - Display the communication records for the last 30 days in a clean, easy-to-read format.

3. **Customer Management**:
   - Provide a central location for managing customer communications with professional presentation and ease of use.

## Features

- **Communication Record Form**: 
   - Allows users to capture customer communication details through a web interface.
   - Fields include:
     - Channel (Drop-down list of communication channels)
     - Direction (Radio button to select Inbound or Outbound)
     - Summary (Text input to summarize the communication)

- **Recent Interactions View**: 
   - Displays communication records that occurred in the last 30 days.
   - Filters and sorts records by date for easy review.

- **Responsive Design**:
   - The user interface is mobile-friendly, making it easy to use on various devices.

## Tech Stack

- **Backend**: Django (Python)
- **Database**: SQLite (for development)
- **Frontend**: HTML, CSS, Bootstrap (for simple and responsive design)
- **Version Control**: Git

## Prerequisites

To run this project locally, ensure you have the following installed:

1. Python (version 3.x)
2. Django (version 3.x or later)
3. SQLite (or an alternative database engine if preferred)

## Installation Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Customer360.git
   cd Customer360
   ```

2. **Create a virtual environment** (recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Migrate the database**:
   ```bash
   python manage.py migrate
   ```

5. **Run the development server**:
   ```bash
   python manage.py runserver
   ```

6. **Access the application**:
   Open a browser and navigate to `http://127.0.0.1:8000/` to use the application.

## Usage

1. **Adding a Communication Record**:
   - Navigate to the communication form using the link provided on the home page.
   - Fill in the required fields (Channel, Direction, and Summary) and submit the form to store the record.

2. **Viewing Recent Interactions**:
   - Visit the "Recent Interactions" page to view communications from the past 30 days.
   - Interactions are displayed in descending order, starting with the most recent.

## Future Enhancements

- **Search Functionality**: Allow users to search for specific communication records based on keywords or date ranges.
- **User Authentication**: Add authentication to restrict access to the communication records and protect customer data.
- **Multiple Communication Channels**: Enable integration with external platforms (email, SMS, etc.) to automatically store communication records.
- **Customer Profiles**: Develop a full-fledged customer profile management system that links communication records to individual customers.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

---

Feel free to explore the project, and don't hesitate to report any issues or suggest new features!
