# Introduction to Django
* Django is a high-level Python web framework that encourages rapid development and clean, pragmatic design. 
* Built by experienced developers, it takes care of much of the hassle of web development, so you can focus on writing your app without needing to reinvent the wheel. It's free and open source.
* What is Django used for?
 - Django can be (and has been) used to build almost any type of website — from content management systems and wikis, through to social networks and news sites. 
 - It can work with any client-side framework, and can deliver content in almost any format (including HTML, RSS feeds, JSON, XML, etc)

## "opinionated" framework:
* Django is "somewhat opinionated", and hence delivers the "best of both worlds". 
* It provides a set of components to handle most web development tasks and one (or two) preferred ways to use them.

![](https://image.slidesharecdn.com/jfokus-jruby-rails-110215090813-phpapp01/95/jruby-rails-awesome-java-web-framework-at-jfokus-2011-18-728.jpg?cb=1297761611)

![](https://i.ytimg.com/vi/GzNYpu_OKvU/maxresdefault.jpg)

## how to code it:
1. `poetry add django`
2. `django-admin help` : 
 - we can use it to start new project: `django-admin startproject project_name .` where the dot means this folder
3. "manage.py": is the entry point to run administrative tasks, we can run it as script( `python manage.py`), 
4. __pycache__ : I should add it to .gitignore, It will be created when I run my code.
5. inside "urls.py" there is "urlpatterns" where I can add my urls, and what code should run 
6. "settings.py": most important file, most sections are documented
 - INSTALLED_APPS: used to add functionality

7. Running the server:
 - `python manager.py runserver`
 - `python manage.py migrate` , now it created tables inside our db
 - db.sqlite : a type of db, it is a light version of sql, It is in a file instead of being on a server. I can see its content : "DB Browers for SQlight"
 - in terminal: ` sqlite3` to enter its shell
 - `.show`
 - `.open db.sqlite3`