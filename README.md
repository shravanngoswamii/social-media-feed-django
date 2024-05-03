# Social Media Feed using Django

This is a Django-based web application that implements a social media feed with features such as user authentication, posting, liking, commenting, searching other users, and managing user profiles.

## Features

- User registration and authentication (signup/login)
- Create, view, like, and comment on posts
- Search for other users
- Manage user profile (change username)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/shravanngoswamii/social-media-feed-django.git
```

2. Navigate to the project directory:

```bash
cd django-social-media-feed
```

3. Create and activate a virtual environment (optional but recommended):

```bash
pip install virtualenv # if not already installed
```
Creating Virtual Environment:
```bash
virtualenv myenv
```
Activating Virtual Environment:
On Windows:
```bash
myenv\Scripts\activate
```
On Mac or Linux:
```bash
source myenv/bin/activate
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

4. Apply database migrations:
On Windows:
```bash
python manage.py makemigrations
```
```bash
python manage.py migrate
```

On Mac or Linux:
```bash
python3 manage.py makemigrations
```
```bash
python3 manage.py migrate
```

6. Create a superuser (optional, but required for admin access):

```bash
python manage.py createsuperuser
```
7. Start the development server:

```bash
python manage.py runserver
```
The application should now be accessible at http://127.0.0.1:8000/.

## Video Demonstration:
https://github.com/shravanngoswamii/social-media-feed-django/assets/123811742/638dbf31-1ee5-4118-8a49-9434de8329ae

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.
