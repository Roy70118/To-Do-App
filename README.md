# To-Do-App
To-Do Application with Django

This is a web-based To-Do application built with Django that allows users to register, log in, and manage their tasks efficiently.
Features

    User Authentication: Users can create an account, log in, and log out securely.
    Task Management: Authenticated users can add new to-do items with the following attributes:
        Title: A brief description of the task.
        Status: Indicates whether the task is 'Completed' or 'Pending'.
        Priority: Sets the urgency of the task with options 1, 2, or 3.

Installation

    Clone the repository:

git clone https://github.com/Roy70118/To-Do-App.git

Navigate to the project directory:

cd To-Do-App

Create a virtual environment:

python -m venv venv

Activate the virtual environment:

    On Windows:

venv\Scripts\activate

On macOS and Linux:

    source venv/bin/activate

Install the required dependencies:

pip install -r requirements.txt

Apply migrations:

python manage.py migrate

Create a superuser (optional, for admin access):

python manage.py createsuperuser

Run the development server:

    python manage.py runserver

    Access the application at http://127.0.0.1:8000/.

Usage

    Register: Navigate to the registration page to create a new account.
    Log In: After registering, log in with your credentials.
    Add To-Do: Once logged in, you can add new to-do items by providing a title, selecting the status (Completed or Pending), and setting the priority (1, 2, or 3).
    Manage Tasks: View, edit, or delete your to-do items as needed.
