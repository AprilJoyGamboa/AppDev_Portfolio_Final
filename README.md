# INTRODUCTION 

"Django Portfolio" is a personal  blog and portfolio website built using Django and HTML and CSS. It includes several pages such as Home, About Me, Projects, Contact and custom 404 pages. The project features a clean and modern design that is fully responsive and optimized for performance. It includes a powerful admin interface for managing the content, and is easy to customize and deploy to a production environment.

# Technologies used
HTML
CSS
JavaScript
Python

# Primary Modules used
Django==4.1.4
whitenoise==6.3.0
psycopg2==2.9.5
django-tinymce==3.5.0

# Pages
Home: The landing page of the website, which displays a brief introduction.
About: A page that provides information about the site owner, their background, and skills.
Contact: A page that contains a contact form for visitors to send messages to the site owner.
Projects: A page that displays a list of portfolio projects.

# Deployment

o deploy this project to a web server, you can follow these general steps:

Set up a web server that can run Python applications. This could be a VPS, a PaaS like Heroku, or a cloud-based server like AWS.
Clone the repository to your server:

# LINk to pythonanywhere

https://davidkarldacallos.pythonanywhere.com/

tart the Django development server, or set up a production server using a WSGI server like uWSGI or Gunicorn.

python manage.py runserver

Access the website using your server's IP address or domain name, and the port number of the server if necessary. For example, if you're running the development server on port 8000, you can access the website at http://your-server-ip:8000/.
