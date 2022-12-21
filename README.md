![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Welcome!

This is the initial project readme.

The last update to this file was: **December 21, 2022**

## Reminders

To install django, `pip3 install 'django<4'`

Use `python3 manage.py runserver` to launch web server

We add the app with `python3 manage.py startapp blog` for example

Then we need to migrate the changes to the database etc with `python3 manage.py migrate`

Remember to update settings.py with all the env vars for secure access to Django and the Elephant DB in the database section

To set up a app/database admin we need `python3 manage.py createsuperuser`

###
import os
import dj_database_url
if os.path.isfile('env.py'):
import env
###

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to *Account Settings* in the menu under your avatar.
2. Scroll down to the *API Key* and click *Reveal*
3. Copy the key
4. In Gitpod, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you so do not share it. If you accidentally make it public then you can create a new one with _Regenerate API Key_.

------

## Release History

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**December 21 2022:** Initial readme and Django/Psycopg2 database setup

------

## FAQ 
**Anything more?**

Not at this time.

---

Happy coding!
