# Django Simple Task Manager

Django Simple Task Manager is a straightforward and efficient to-do list application built with Django. It's designed to help you manage your daily tasks in a web-based interface, ensuring that you stay organized and productive. This project is ideal for those looking to understand the fundamentals of Django while working on a practical application.

## Features

- **User Authentication:** Secure login and registration system to keep your tasks private.
- **Task Management:** Create, update, delete, and mark tasks as completed.
- **Categorization:** Organize tasks into categories for better management.
- **Search Functionality:** Quickly find tasks using the search feature.
- **Responsive Design:** Accessible on various devices, ensuring a seamless user experience.

## Installation

Before you begin, ensure you have Python and Django installed on your system. If not, follow the official guides to install [Python](https://www.python.org/downloads/) and [Django](https://docs.djangoproject.com/en/stable/topics/install/).

1. **Clone the repository:**

   ```
   git clone https://github.com/assaf-malki/django-simple-task-manager.git
   cd django-simple-task-manager
   ```

2. **Install dependencies:**

   ```
   pip install -r requirements.txt
   ```

3. **Initialize the database:**

   ```
   python manage.py makemigrations
   python manage.py migrate
   ```

4. **Run the development server:**

   ```
   python manage.py runserver
   ```

   The application should now be running on [http://localhost:8000](http://localhost:8000).

## Usage

After launching the application, navigate to [http://localhost:8000](http://localhost:8000) in your web browser. Here you can register a new account or log in with existing credentials. Once logged in, you can start adding, managing, and organizing your tasks.

## License

Distributed under the Apache-2.0 License. See `LICENSE` for more information.
