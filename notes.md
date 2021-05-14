# Getting Started with virtualenv

## On Windows
1. Open the **cmd** shell.
2. Check Python version by running `py --version`.<br>
*Note: Make sure the version listed is the same as the version you installed.<br>
This project uses version 3.9.5.*

3. Navigate to the root project directory `PunBuggy`.
4. Run `PunBuggy\scripts\activate.bat` to enter the **virtualenv**.<br>
*Note: Each time you start a new command prompt, you’ll need to activate the environment again.*<br>
[Further Reading](https://dev.to/koladev/build-a-crud-application-using-django-and-react-5389)

# Building Django locally
1. First, make sure you're in the **virtualenv**. Then, run `py -m pip install django`.
2. To verify that Django installed correctly, run `django-admin --version`.
3. Run `pip install django django-rest-framework`.
4. To create the server project, be sure to run `django-admin startproject PROJECTNAME .` with the period.
5. To deploy the server at `127.0.0.1:8000`, run `python manage.py runserver`.
