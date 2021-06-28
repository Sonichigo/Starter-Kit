# Starter-Kit

Sample API layout structure to be used as a baseline for other apps

## Dependencies

- [FLASK](https://palletsprojects.com/p/flask/): Python server of choise
- [FLASGGER](https://github.com/flasgger/flasgger): Used to generate the swagger documentation
- [FLASK-MARSHMALLOW](https://flask-marshmallow.readthedocs.io/en/latest/): My favourite serializer
- [APISPEC](https://apispec.readthedocs.io/en/latest/): Required for the integration between marshmallow and flasgger

## Set Up

1. Check out the code
2. Install requirements
    ```
    pipenv install
    ```
3. Start the server with:
    ```
   pipenv run python -m flask run
    ```
   
4. Visit http://localhost/api for the home api
   
## Tests

The code is covered by tests, to run the tests please execute

```
pipenv run python -m unittest
```
