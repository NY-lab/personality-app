# Personality Test Web Application

## Description
The Personality Test Web Application is a Flask-based web application that allows users to take a personality test and receive results based on their answers. The application provides a set of questions for the user to answer, calculates a total score, and categorizes the user's personality based on the score.

## Features

- **User Authentication:** Users can register, log in, and log out of their accounts.
- **Personality Test:** Users can answer a set of questions to determine their personality type.
- **Result Categorization:** The application categorizes users into different personality types based on their test scores.
- **User Dashboard:** Authenticated users have access to a personalized dashboard displaying their test results.
- **Logging:** The application logs user actions and errors for monitoring and debugging purposes.

## Technologies Used

- **Flask:** Web framework for building the application.
- **MySQL:** Database management system for storing user data and test results.
- **Redis:** In-memory data structure store for caching and session management.
- **HTML/CSS/JavaScript:** Front-end technologies for creating the user interface and interactivity.
- **Logging:** Python's `logging` module is used to log user actions and errors.

## Setup Instructions

1. **Clone the Repository:**
   ```bash
   git clone <repository_url>
   cd personality-test-app
   ```

2. **Set Up Virtual Environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use venv\Scripts\activate
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Database Configuration:**
   - Set up a MySQL database and update the configuration in `appconfig.properties`.
   - Create the necessary tables using the provided SQL queries.

5. **Redis Configuration:**
   - Install and configure Redis for session management.

6. **Run the Application:**
   ```bash
   python app.py
   ```
   The application will be accessible at `http://localhost:5000`.

## File Structure

- `app.py`: Main application file containing routes and configurations.
- `templates/`: HTML templates for different pages.
- `static/`: CSS and JavaScript files for styling and interactivity.
- `config.py`: Configuration file for the application.
- `appconfig.properties`: Configuration file containing database and session configurations.
- `requirements.txt`: List of Python dependencies.

## Usage

- Access the application at `http://localhost:5000`.
- Users can register, log in, and take the personality test.
- Test results are displayed based on the user's answers.
- Authenticated users can view their test history on the dashboard.

## Logging

- Application actions and errors are logged in the `flask_app.log` file.
- Logging configuration can be adjusted in `config.py`.

## Contributors

- [Your Name](link_to_your_profile) - Role/Contribution

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this template according to your specific project details and contributions.