

# Job Application Form App

This is a Django-based web application for job applicants to fill in their personal information and submit it. The app allows the user to input their first name, last name, email, available start date, and their employment status (employed, unemployed, self-employed, or student). When the user submits the form, the data is stored in a database using Django's ORM, and the user receives a confirmation email.

## Prerequisites

- Python 3.6 or higher
- Django 3.2 or higher

## Installation

1. Clone the repository
   ```
   git clone https://github.com/username/job-application-form-django.git
   cd job-application-form-django
   ```

2. Install the dependencies
   ```
   pip install -r requirements.txt
   ```

3. Set up the database
   ```
   python manage.py makemigrations
   python manage.py migrate
   ```

4. Set up environment variables
   ```
   export SECRET_KEY=<your-secret-key>
   export EMAIL_HOST=<your-email-host>
   export EMAIL_PORT=<your-email-port>
   export EMAIL_HOST_USER=<your-email-host-user>
   export EMAIL_HOST_PASSWORD=<your-email-host-password>
   export EMAIL_USE_SSL=True
   ```

5. Run the application
   ```
   python manage.py runserver
   ```

## Usage

Open your web browser and go to http://localhost:8000. Fill in the job application form and click the submit button. The data will be stored in the database, and the user will receive a confirmation email.
