# Job Board Application

Welcome to the Job Board Application repository! This application is designed to help both job seekers and employers in the process of finding jobs and hiring people.

## Features
- Job listings for available positions
- Submission of job applications
- Posting of job openings
- User authentication for job seekers and employers
- Search functionality to find relevant job listings

## How to Run Locally

To run the Job Board Application locally, follow these steps:

1. Clone this repository to your local machine using the following command:
    ```
    git clone https://github.com/ezrablackfish2/Job-Board-Django
    ```

2. Navigate to the project directory:
    ```
    cd Job-Board-Django
    ```

3. Create a virtual environment:
    ```
    python -m venv venv
    ```

4. Activate the virtual environment:
   - On Windows:
    ```
    venv\Scripts\activate.bat
    ```
   - On macOS and Linux:
    ```
    source venv/bin/activate
    ```

5. Install the required dependencies:
    ```
    pip install -r requirements.txt
    ```

6. Set up your database by running migrations:
    ```
    python manage.py migrate
    ```

7. Create a superuser for accessing the admin panel:
    ```
    python manage.py createsuperuser
    ```

8. Start the Django development server:
    ```
    python manage.py runserver
    ```

9. Access the application through your web browser at `http://localhost:8000`.

## Contributors
- [Ezra Yeneneh](https://github.com/ezrablackfish2/)
- [John](https://github.com/johnnybeatzxxd/)
