# Instalation

Create and activate environment
    ```
    #Create
    virtualenv -p python3 env
    ```
    ```
    #activate
    source env/bin/activate
    ```

Migrate and Migration app project:
    ```
    #migration
    python manage.py makemigrations projects
    ```

    ```    
    #migrate
    python manage.py migrate projects
    ```

Add post and save it in python shell django:
    ```
    #add post
    p1 = Project(
    title='My First Project',
    description='A web development project.',
    technology='Django',
    image='img/project1.png'
    )
    ```

    ```
    #save it
    p2.save()
    ```

Running django project

    ```
    python manage.py runserver
    ```