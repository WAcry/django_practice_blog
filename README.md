# Django Self Practice

A tiny blog application based on Django, Bootstrap and SQLite.

![](https://raw.githubusercontent.com/Quakiq/tinyimages/main/img/202204012018410.png)

![](https://raw.githubusercontent.com/Quakiq/tinyimages/main/img/202204012018811.png)

Deploy Guide:

    1. Start the SQLite database server using db.sqlite3
    2. run `python manage.py migrate` in terminal to apply the database migrations
    3. run `python manage.py createsuperuser` in terminal to create a superuser
    4. Start the django server by command `python manage.py runserver`
    5. Go to http://localhost:8000/blog/index/ to see the blog posts

Manage Articles:

    run tools/import_data.py to import articles from data/articles to the database,
    or you can manage articles using the admin page http://localhost:8000/admin

