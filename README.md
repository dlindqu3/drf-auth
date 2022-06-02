## Lab - class 33
## Author - Dwight Lindquist 
## Tests - 
  - run containers/images
  - create a superuser
  - thunderclient: 
    - post request to /api/token/
        - include in request body: {
        "username":"<your username>","password":“<your password>"
	      }
    - get request to /api/v1/books
        - you must enter access token under auth “Bearer”, without “”
    - refresh: post to /api/refresh/
  - python manage.py test (this runs prior labs' tests)