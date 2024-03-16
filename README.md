# Student Management System

This is a Flask-based web application for managing students, courses, and their enrollments.

## Installation

1. Clone the repository:

    ```bash
    git clone <repository_url>
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up the database:

    - Make sure you have SQLite installed.
    - Initialize the database by running:

        ```bash
        flask db init
        flask db migrate
        flask db upgrade
        ```

## Usage

1. Run the application:

    ```bash
    flask run
    ```

2. Access the application in your web browser at `http://localhost:5000/`.

## Features

- **View Students and Courses**: Navigate through the list of students and courses.
- **Add Students and Courses**: Add new students and courses to the system.
- **Update and Delete**: Modify existing student and course records, including enrollment management.
- **Enrollment Management**: Enroll students into courses and withdraw them when needed.

## Technologies Used

- Flask
- Matplotlib
- SQLAlchemy
- SQLite
- Python
- HTML
- CSS
## Contributors

- [SUJAL RAJ PRADHAN](https://github.com/SujalPradhan)


Make sure to replace `<repository_url>`, `Your Name`, `Contributor's Name`, and `your_username`/`contributor_username` with appropriate values. You can also add more sections or details as needed for your specific project.
