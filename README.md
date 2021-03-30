# recipe-app-api
Source code for a recipe app API, using the django and django REST frameworks. The application is contained as a docker image, and was developed using Test Driven Development. The standard SQLite3 db was replaced instead with PostgreSQL and all testing and linting is automated through Travis CI when committing and pushing to GitHub.

The normal user model was replaced with a custom user model that replaces the username field with an email field.
