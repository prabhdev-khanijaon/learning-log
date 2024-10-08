*NOTE* Encountered an error uploading Django, pip and other files to this repository. App may not work for you if cloned. Feel free to contact me .

# Learning Log Project
# Overview
Learning Log is a web application that allows users to track topics they are learning about and record detailed journal entries as they progress. This project demonstrates web development skills using Django and provides a platform for users to create, view, and manage their learning topics and entries. The app includes user authentication, topic creation, and entry management, offering a full-stack solution from front-end UI to back-end data handling.

## This project highlights key skills relevant for a data analyst role:
Data management with Django's ORM.

Web development using Django.

Basic understanding of database structures.

Data presentation and user interaction.

## Skills Demonstrated
Data Management: The project showcases how to handle data through Django models and integrate database operations for storing and retrieving user-generated content.

User Interaction and Data Entry: Implementing forms and views that allow users to interact with the data, manage their learning topics, and update entries.

Django Web Development: Hands-on experience with Django's web framework, including user authentication, form handling, and view rendering.

## Key Features
User Registration & Authentication: Users can sign up, log in, and securely manage their learning topics and entries.

Create, Read, Update, Delete (CRUD) Operations:

Topics: Users can create new learning topics and manage their progress.

Entries: Journal-style entries can be added, viewed, updated, and deleted for each topic.

Responsive UI: Uses django-bootstrap5 to provide a clean and responsive user interface.

## Future Improvements
Data Visualization: Integrating data visualization features using Plotly or Matplotlib to provide insights into users' learning progress.

User Notifications: Adding notifications or reminders for users to update their learning logs regularly.

Enhanced Security: Implementing more robust security measures such as two-factor authentication and stronger password policies.

## How to Run the Project Locally
### Clone the Repository:

bash

Copy code

git clone https://github.com/your-username/learning-log.git

cd learning-log

### Set Up Virtual Environment:

Create and activate a virtual environment to manage dependencies:

bash

Copy code

python -m venv ll_env

source ll_env/bin/activate  # On Windows use ll_env\Scripts\activate

### Install Dependencies:

### Install all necessary dependencies from the requirements.txt file:

bash

Copy code

pip install -r requirements.txt

### Run the Server:

### Start the Django development server:

bash

Copy code

python manage.py runserver

The app will be accessible at http://127.0.0.1:8000/.




