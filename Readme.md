# Flask app template
This template is created from blog demo in Master Flask Web Develop.
It has almost all modules except flask-bable, open-id.


## webapp Modules details:
1. admin
    App administrator pages include: database models
    
2. api
    flask restful defined
    
3. auth
    It includes user authorization
    
4. blog
    web pages defined in this module, celery task also defined
    
5. cli.py
    It includes command-line commands define
    
## test modules details:
It contains url and webpage test functions.


## other file details:
1. celery_runner.py
    It create celery worker, it must be run independently with flask app.
    
2. config.py
    It contains all configuration.
    
3. 