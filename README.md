# Tweeter

## Overview
Tweeter is a simple social media application built using Django, allowing users to create, view, edit and delete tweets. Users can also register, log in, and log out. The application supports image uploads with tweets and provides a search functionality to find tweets by text or username.


## Features
* User registration and authentication
* Create, view, edit and delete tweets
* Upload images with tweets
* Search functionality for tweets
* Responsive design using Bootstrap


## Technologies Used
* **Django:** A high-level Python web framework
* **SQLite:** Database for storing user and tweet data
* **Bootstrap:** Frontend framework for responsive design
* **Pillow:** Python Imaging Library for image handling


## Screenshots
### Home Screen
![Home Screen](https://github.com/user-attachments/assets/c3d1c672-9c15-4ba5-a12a-a06aae9c1329)

### User Registration
![Register](https://github.com/user-attachments/assets/edffa934-fd65-4baa-99fe-d3180d3114cf)

### Login Page
![Login](https://github.com/user-attachments/assets/8e1d8aa4-80e8-4898-9b4c-1bc092c40ab3)

### Delete a tweet
![delete](https://github.com/user-attachments/assets/6e6f6a7e-26b7-4f2b-9ae1-5314090424d3)


## Installation
### Prerequisites
* Python 3.8 or higher
* pip (Python package installer)

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/rathore-nikhil/Tweeter.git
   cd Tweeter

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
4. **Run database migrations:**
   ```bash
   python manage.py migrate
5. **Create a superuser  (optional, for accessing the admin panel):**
   ```bash
   python manage.py createsuperuser
6. **Start the development server:**
    ```bash
   python manage.py runserver
7. **Access the application:** Open your web browser and go to **http://127.0.0.1:8000/**.

## File Structure
 ```
/Tweeter
│
├── /media                # Directory for uploaded media files
├── /static               # Directory for static files (CSS, JS)
├── /tweet                # Django app for handling tweets
│   ├── /migrations       # Database migrations
│   ├── /templates        # HTML templates for the app
│   ├── /forms.py         # Forms for tweet and user registration
│   ├── /models.py        # Database models
│   ├── /views.py         # Views for handling requests
│   └── /urls.py          # URL routing for the app
│
├── /Tweeter              # Main project directory
│   ├── /settings.py      # Project settings
│   ├── /urls.py          # Main URL routing
│   ├── /wsgi.py          # WSGI configuration
│   └── /asgi.py          # ASGI configuration
│
├── manage.py             # Django management script
└── requirements.txt      # Python dependencies
```


## Usage
* **Register:** Create a new account to start tweeting.
* **Login:** Access your account to create, edit, or delete tweets.
* **Create Tweet:** Use the form to submit a new tweet with optional image upload.
* **Edit/Delete Tweet:** Manage your tweets from the tweet list.
* **Search:** Use the search bar to find tweets by text or username.


