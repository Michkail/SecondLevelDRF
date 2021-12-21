# SecondLevelDRF
```
Check the proper acquisition of all your new programming skills by
creating a new Web API which will provide a list of Quotes!
```

##  Client will be able to communicate with our Web API from 2 URL Endpoints:
```
1.  Create/Update/Delete permissions must be granted 
    exclusively to admin users

2   Anonymous users must be able to retrieve the available 
    records paginated in groups of 30 quotes 
```

## Folder Structure
```
    FirstLevelDRF
        |\_____ job_slurp
        |         |\_____ __pycache__
        |         |         |\_____ __init__.cpython-39.pyc
        |         |         |\_____ settings.cpython-39.pyc
        |         |         |\_____ urls.cpython-39.pyc
        |         |          \_____ wsgi.cpython-39.pyc
        |         |  
        |         |\_____ __init__.py
        |         |\_____ settings.py
        |         |\_____ urls.py
        |          \_____ wsgi.py
        |
        |\_____ slurp
        |         |\_____ __pycache__
        |         |         |\_____ __init__.cpython-39.pyc
        |         |         |\_____ admin.cpython-39.pyc
        |         |          \_____ models.cpython-39.pyc
        |         |    
        |         |\_____ migrations
        |         |         |\_____ __pycache__
        |         |         |         |\_____ __init__.cpython-39.pyc
        |         |         |          \_____ 0001_initial.cpython-39.pyc
        |         |         |
        |         |         |\_____ __init__.py
        |         |          \_____ 0001_initial.py
        |         |
        |         |\_____ __init__.py
        |         |\_____ admin.py
        |         |\_____ apps.py
        |         |\_____ models.py
        |         |\_____ tests.py
        |          \_____ views.py
        |
         \_____ manage.py       
```

## Only one model is needed for the project, you can call it SlurpOffer. It must have the following fields:
```
♬  quote_author 
♫  quote_body  
♩  contenx
♪  source
♬  created_at
```