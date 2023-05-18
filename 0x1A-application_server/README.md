Application server

Background Context


This web infrastructure is already serving web pages via Nginx that was installed in my first web stack project. While a web server can also serve dynamic content, this task is usually given to an application server. In this project added this piece to the infrastructure, plug it to my Nginx and make is serve my Airbnb clone project.

Resources

*Application server vs web server

*How to Serve a Flask Application with Gunicorn and Nginx on Ubuntu 16.04 (As mentioned in the video, do not install Gunicorn using virtualenv, just install everything globally)

*Running Gunicorn

*Be careful with the way Flask manages slash in route - strict_slashes

*Upstart documentation

Requirements

*Everything Python-related must be done using python3

*All config files must have comments.
