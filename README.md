# Instalation

Create and activate environment
    ```
    virtualenv -p python3 env
    ```

    ```
    source env/bin/activate
    ```

Migrate and Migration app project:
    ```
    python manage.py makemigrations projects
    ```
    ```
    python manage.py migrate projects
    ```

Add post and save it in python shell django:
    ``` 
    p1 = Project(
    title='My First Project',
    description='A web development project.',
    technology='Django',
    image='img/project1.png'
    )
    ```
    ```
    p2.save()
    ```

Running django project

    ```
    python manage.py runserver
    ```