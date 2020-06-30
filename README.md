<p align="center">
    <img src="https://raw.githubusercontent.com/viral-sangani/blog.viralsangani.me/master/static/logo/linkedin_banner_image_2.jpg" alt="Personal Logo">
    <br>
    <br>
</p>

<p align="center">
🐍 django-boilerplate is a project for jumpstarting production-ready Django projects quickly. 🔥
</p>

<p align="center">
    Project Documentation URL - <a href="https://django-boilerplate-docs.viralsangani.me/">https://django-boilerplate-docs.viralsangani.me/</a>
</p>

# Django Boilerplate

## 🌟 Features

- Build for Django 3.0
- Works with Python 3.8
- Renders Boilerplate Django projects with 98% starting test coverage
- 12-Factor based settings using django-environ
- We belive in SSL, secure by default in Production.
- Comes with custom user model
- Media storage with AWS S3 in Production
- Static file handling via AWS S3 in Production
- Already written test in unittest and pytest
- Registration using django-allauth
- Custom and optimized settings for development and production
- SMTP already configired for AWS SES. (Mailgun, Anymail is optional)
- Currently only works with PostgreSQL
- pre-commit already configured for identifying simple issues
- Sentry intregration already configures for error logging
- Instaructions to deploy on PythonAnywhere

## Settings

Shifted to - [https://django-boilerplate-docs.viralsangani.me/docs/settings](https://django-boilerplate-docs.viralsangani.me/docs/settings)

## Basic Commands

#### Setting Up Your Users

- To create a **normal user account**, just go to Sign Up and fill out the form. Once you submit it, you'll see a "Verify Your E-mail Address" page. Go to your console to see a simulated email verification message. Copy the link into your browser. Now the user's email should be verified and ready to go.

- To create an **superuser account**, use this command::

```bash
python manage.py createsuperuser
```

For convenience, you can keep your normal user logged in on Chrome and your superuser logged in on Firefox (or similar), so that you can see how the site behaves for both kinds of users.

### Type checks

Running type checks with mypy:

```bash
mypy django_boilerplate
```

#### Test coverage

To run the tests, check your test coverage, and generate an HTML coverage report::

```bash
coverage run -m pytest
coverage html
open htmlcov/index.html
```

#### Running tests with py.test

```bash
pytest
```

### Sentry

Sentry is an error logging aggregator service. You can sign up for a free account at [https://sentry.io/signup/](https://sentry.io/signup/) or download and host it yourself.
The system is setup with reasonable defaults, including 404 logging and integration with the WSGI application.

You must set the DSN url in production.

### Deployment

The following details how to deploy this application.
[Deployment on PythonAnywhere](https://django-boilerplate-docs.viralsangani.me/docs/deployment_on_pythonanywhere)

### 💜 Thanks

Special thanks to [@tanaypratap](https://github.com/tanaypratap) sir, and [2020.teamtanay.jobchallenge.dev](https://github.com/tanaypratap/teamtanay.jobchallenge.dev) for encouraging student like me to create amazing projects and help us to grow.
