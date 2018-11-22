src: https://tutorial.djangogirls.org/en/django_start_project/

## How The Internet Works

src: https://www.youtube.com/watch?v=oM9yAA09wdc

### Parts of a URL
E.g.: `http://djangogirls.org/london`

- How? - `http://`
- Where? - `djangogirls.org/`
- Who? - `london/`

- The *Domain Name Server* (DNS) is the "address book" of the internet. It contains IP addresses (or maybe serves them?). Remember those old-school things?
- The internet is made of **servers**. Servers are machines that only store data, and serve it to clients. And they're interconnected by, amazingly, [actual physical cables](https://www.submarinecablemap.com).
- A **packet** is a letter, an **IP address** is the address on the letter, and the, well, contents of the letter requesting something is the **GET request**.
- If you really want to know about the ugly details of a HTTP request: http://www.rfc-editor.org/info/rfc7230


## Parts of Django

 - `settings.py` - contains website config stuff
 - `urls.py` - Contains a list of patterns used by `urlresolver`

## Frequently-used commands

 - Start server: `python3 manage.py runserver`
 - Create/update database: `python3 manage.py migrate`
 - Create app (or Python module?): `python3 manage.py startapp blog`. Note that everytime a new app is created, you'll still need to tell Django to use it: add it to the `INSTALLED_APPS` list in `settings.py`
 - create admin: `python3 manage.py createsuperuser`
