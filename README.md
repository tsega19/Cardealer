
# Car Dealer website
A simple project based on Online Car Dealer Website which uses Python with Django Web
Framework. The project contains all the important features which can be in use by any car buying
and selling agents with simple methods. This system as well as the web application’s concept is
all clear, it’s the same as real-life scenarios and well-implemented on it. In particular, this car
dealer website project in Django focuses mainly on dealing with new and used cars. In addition,
the system allows for managing customers and car records. To be more precise, the system helps
to keep track of customers’ inquiries.

## Getting Started


- Python 
- PostgreSQL 
### Installation

1. Clone the repository:

   ```bash
   git clone <repository_url>
````

2. Create and activate a virtual environment (optional but recommended):

   ```bash
   python -m venv env
   source env/bin/activate
   ```

1. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

1. Create a PostgreSQL database named "cardealer_db".

1. Configure the PostgreSQL database credentials in the project's settings.py file.

1. Apply the database migrations:

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

### Running the Application

Start the development server:

```bash
python manage.py runserver
```

Access the application in your web browser at `http://localhost:8000`.

## Creating an Admin Account

To access the administrative features of the application, you need to create a superuser account. Follow these steps:

1. Run the following command:

   ```bash
   python manage.py createsuperuser
   ```

1. Provide a username, email (optional), and password when prompted.

1. Your superuser account is now created and can be used to log in to the admin interface.

## Contributing

If you'd like to contribute to this project, please follow these guidelines...

Make sure to replace `<repository_url>` with the actual URL of your Git repository. You can also customize other sections of the README file according to your project's specific details and requirements.```
