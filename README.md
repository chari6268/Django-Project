Here are some common Django commands used for project management:

### 1. Start a New Project
```bash
django-admin startproject projectname
```
Creates a new Django project named `projectname`.

### 2. Start a New App
```bash
python manage.py startapp appname
```
Creates a new Django app named `appname` within the project.

### 3. Run the Development Server
```bash
python manage.py runserver
```
Starts the Django development server.

### 4. Make Migrations
```bash
python manage.py makemigrations
```
Creates new migrations based on the changes detected in your models.

### 5. Apply Migrations
```bash
python manage.py migrate
```
Applies the migrations to the database.

### 6. Create a Superuser
```bash
python manage.py createsuperuser
```
Creates a superuser account for accessing the Django admin site.

### 7. Collect Static Files
```bash
python manage.py collectstatic
```
Collects all static files into the directory specified by `STATIC_ROOT`.

### 8. Check for Issues
```bash
python manage.py check
```
Checks the entire Django project for potential issues.

### 9. Open the Django Shell
```bash
python manage.py shell
```
Opens the interactive Django shell.

### 10. Test the Project
```bash
python manage.py test
```
Runs the tests for the Django project.