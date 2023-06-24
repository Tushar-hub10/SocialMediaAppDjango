# Django Social Media App

Django Social Media App is a web application built with Django that allows users to create accounts, post content, and interact with other users.

## Features

- User registration and login
- Create, edit, and delete posts
- User profile page

## Installation

1. Clone the repository:

git clone https://github.com/your-username/social-media-app.git

css
Copy code

2. Change to the project directory:

cd social-media-app

markdown
Copy code

3. Install the dependencies:

pip install -r requirements.txt

markdown
Copy code

4. Apply database migrations:

python manage.py migrate

markdown
Copy code

5. Start the development server:

python manage.py runserver

less
Copy code

6. Open your web browser and navigate to [http://localhost:8000](http://localhost:8000) to access the application.

## Configuration

The application uses environment variables for configuration. Create a `.env` file in the project directory and provide the following variables:

SECRET_KEY=your_secret_key
DEBUG=False
DATABASE_URL=your_database_url

python
Copy code

Replace `your_secret_key` with your Django secret key, `your_database_url` with your database connection URL, and adjust other settings as needed.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).# SocialMediaAppDjango
