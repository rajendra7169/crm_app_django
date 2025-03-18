# CRM App Django

A Customer Relationship Management (CRM) application built using Django.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact Information](#contact-information)

## Introduction

The CRM App Django is a web-based Customer Relationship Management application designed to help businesses manage interactions with current and potential customers. This project leverages the Django framework to provide a robust and scalable solution for CRM needs.

## Features

- User Registration and Authentication
- Customer Management
- Lead Management
- Task Management
- Dashboard and Reporting
- User-friendly Interface

## Technologies Used

- **Backend:** Django
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite (default, can be configured for other databases)
- **Other Technologies:** Django REST Framework

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/rajendra7169/crm_app_django.git
   cd crm_app_django
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python3 -m venv env
   source env/bin/activate   # On Windows use `env\Scripts\activate`
   ```

3. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables:**
   Create a `.env` file in the root directory and add the necessary environment variables as per the `.env.example` file.

5. **Apply the migrations:**
   ```bash
   python manage.py migrate
   ```

6. **Run the server:**
   ```bash
   python manage.py runserver
   ```

## Usage

1. **Register a new user account.**
2. **Log in with your credentials.**
3. **Add and manage customers, leads, and tasks.**
4. **View dashboard and reports to track CRM activities.**

## Contributing

We welcome contributions to enhance the CRM App Django. To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a Pull Request.

## License

This project is currently not licensed under any specific license. Feel free to contribute and use as per your needs.

## Contact Information

For any inquiries or feedback, please contact:

- **Rajendra Pandey**: [rajendrapandey199971@gmail.com](mailto:rajendrapandey199971@gmail.com)

---

Thank you for using the CRM App Django!

