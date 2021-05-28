# Instalation

- Create environment: ```$ virtualenv -p python3 env```

- activate environment: ```$ source env/bin/activate```

- Migrate and Migration app project: ```$ python manage.py makemigrations projects```

- Migrate app: ``` $ python manage.py migrate projects```

- Add post and save it in python shell django:

```python
    $ p1 = Project(
        title='My First Project',
        description='A web development project.',
        technology='Django',
        image='img/project1.png'
        )

    $ p2.save()
```

Running django project

    $ python manage.py runserver