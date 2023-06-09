
# Test Django Book API

Description test: Using Django Framework, create an interface that allows to search books by name and/or by author using this API https://openlibrary.org/developers/api. It should show the books’ most useful information in the results.

## Possible approaches:
- Consume the API from Python views.
- Create models and sync the content.



## Run project Local

You need install Python 3.9^

- [Link to download Python](https://www.python.org/downloads/)

Clone the project from repository in any folder:

```bash
git clone https://gitlab.com/ivanuribe39/django_book_api.git
```

Within the project we are going to activate a virtual environment and install the necessary libraries.

Create virtual environment:

```bash
python -m venv venv
```

Activate to Linux or Mac (bash o zsh):
```bash
source venv/bin/activate
```

Activate to Windows (CMD):
```bash
venv\Scripts\activate.bat
```

Install requirements project:
```bash
pip install -r requirements.txt
```

Run Server Django
```bash
python manage.py runserver
```

And show this:
```bash
June 03, 2023 - 09:23:00
Django version 4.2.1, using settings 'django_book_api.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
```


## References

 - [Django Framework](https://docs.djangoproject.com/en/4.2/)
 - [Requests Python](https://requests.readthedocs.io/en/latest/)
 - [Virtual envirroment Python](https://docs.python.org/3/library/venv.html)


## Contributing

Contributions are always welcome!
