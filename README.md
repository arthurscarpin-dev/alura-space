# ALURA SPACE
A photo gallery of the space developed in Django.

### Tech Stack:
<p align="left">
    <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=python,django,sqlite"/>
    </a>
</p>

### Graphical interface:
![alura-space](https://github.com/user-attachments/assets/d28093a0-648e-4370-92ca-5ba98ea7beb6)

### How to run?
1. Clone the remote repository.
```
git clone git@github.com:arthurscarpin-dev/alura-space.git
```

2. Create the Python virtual environment.
```
python -m venv venv
```

3. Activate the virtual environment.
* Microsoft Windows
```
.\venv\Scripts\Activate
```
* Linux or MacOS
```
source venv/bin/activate
```

4. Install the libraries found in the **requirements.txt** file
```
pip install -r requirements.txt
```

5. Perform SQLite Migration.
```
python manage.py migrate
```

6. Create Django super user.
```
python manage.py createsuperuser
```

7. Run the application.
```
python manage.py runserver
```
