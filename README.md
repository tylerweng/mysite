# Intro Django Project

## Getting Started

### PostgreSQL
```python
sudo -u postgres psql postgres # log in as default superuser to default db
```

```postgresql
CREATE DATABASE mydatabase;
CREATE USER mydatabaseuser WITH PASSWORD 'mypassword';
GRANT ALL PRIVILEGES ON mydatabase to mydatabaseuser;
ALTER USER mydatabaseuser CREATEDB;
```

### Django
```python
python manage.py makemigrations # creates migrations
python manage.py migrate # migrates changes
python manage.py runserver # runs server
```

## References
[Tutorial](https://docs.djangoproject.com/en/1.11/intro/tutorial01/)
