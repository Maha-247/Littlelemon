Description

This is the final assignment for the Backend Developer Capstone Course of the Meta Backend Developer Professional Certificate on Coursera.


Project Structure

The project is composed of two apps, api and restaurant. The api app serves API endpoints of the project, while the restaurant app serves its frontend. The config (the project folder) directory holds the major settings of the project


Installation

install the dependencies

pipenv install
Activate the virtual environment

pipenv shell


Endpoints for api app

http:127.0.0.1:8000/api/menu-items
http:127.0.0.1:8000/api/menu-items/{menu-itemId}
http:127.0.0.1:8000/api/bookings
http:127.0.0.1:8000/api/bookings/{bookingId}


Endpoints for djoser app

http://127.0.0.1:8000/auth/users/
http://127.0.0.1:8000/auth/users/me/
http://127.0.0.1:8000/auth/users/confirm/
http://127.0.0.1:8000/auth/users/resend_activation/
http://127.0.0.1:8000/auth/users/set_password/
http://127.0.0.1:8000/auth/users/reset_password/
http://127.0.0.1:8000/auth/users/reset_password_confirm/
http://127.0.0.1:8000/auth/users/set_username/
http://127.0.0.1:8000/auth/users/reset_username/
http://127.0.0.1:8000/auth/users/reset_username_confirm/


Endpoints for simplejwt app

http:127.0.0.1:8000/api/token/login/
http:127.0.0.1:8000/api/token/refresh/
