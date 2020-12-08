# About

Movie-ratings is a web application where movie lovers can rating - comment movies and create a community to share their passion.

# Architecture

The backend application is separated with the frontend application even if the are in the same repository. The frontend application is a SPA (Single Page Application) developed in React.js and the backend application is a RESTFull API developed in Python Django/DjangoRestFramework

# Dependencies:
## Backend

- Python 3.*
- django
- djangorestframework
- django-rest-knox
- dj-database-url
- corsheaders

## Frontend
- axios: ^0.21.0
- node-sass: ^5.0.0
- react: ^17.0.1
- react-dom: ^17.0.1
- react-router-dom: ^5.2.0
- react-scripts: 4.0.1

# Directories:

The backend application files are located in `api` directory and the frontend application files are located in `frontend` directory. The `movierating` directory contain the django default application.

# Run in Local

Clone this repository, cd into the repository then install backend dependencies with the following command `pip install -r requirements.txt`, make sure you have python 3.* installed. To start the backend application ru `python manage.py runserver`, the application will running on `http://127.0.0.1:8000`. 

Change directory to the frontend application and install the frontend application dependencies by executing this command `npm install`, make sure you have the latest stable version of  Node.js and NPM installed. Then run run `npm start` to start the frontend application, the application will be running on port `http://localhost:3000`.

# Contribution

All contribution are welcoming. Clone this repository and make sure to create your own working branch, your working branch should contain a README file that detail your contribution. When you finish working to your branch you can submit a pull request to the `main` branch.

### Todo:

 - Integrate the Socket.io to the backend and implement the live chat api endpoints.
 - Implement the live chat in the frontend.

# Licence

MIT © [danielkanangila](https://github.com/danielkanangila)