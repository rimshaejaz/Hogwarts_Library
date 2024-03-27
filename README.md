# Hogwarts Library Database 🧙🏼📚

## Description
As part of a term long project, I worked in collaboration with [Joel Gilger](https://github.com/jgiggler) to create a Flask app that helps manage a library database system. 
Users are able to perform CRUD operations on various tables which include, one-to-one, many-to-one, and many-to-many relationships.
Here is an overview of the project which discusses the database outline, schema, and includes screenshots of the UI: [CS340 Project
](https://docs.google.com/document/d/1xjbcS9OL6N6IfLD_cm-4Dt98i-0t2rQta1I2JeIUrxw/edit?usp=sharing).

## How to View 
In order to view this project, the user must be on OSU's VPN or physically connected to the on campus internet. You can find information on connecting to the VPN [here
](https://oregonstate.edu/).

The MySQL database you will be using for the project will also need to be created. In the course, this was done using phpMyAdmin. 

**Build & Run:**
1. Connect to any of the OSU flip engineering servers, connect via VPN or be connected to the oncampus internet, and clone the repository.
```
git clone https://github.com/rimshaejaz/Hogwarts_Library.git
```

2. Go to the [CS340_starter_flask_app](https://github.com/osu-cs340-ecampus/flask-starter-app) repository folder and setup a new Python virtual environment for Flask, then install related dependencies.

3. Create the databases for the project in your phpMyAdmin account. 

4. On the app.py file, change lines 14-16 to accuratley reflect your phpMyAdmin log in credentials. 
```
app.config['MYSQL_USER'] = 'cs340_ONID'
app.config['MYSQL_PASSWORD'] = 'XXXX' #last 4 of onid
app.config['MYSQL_DB'] = 'cs340_ONID'
```
5. Replace 4546 with a random port number, run "source venv/bin/activate", then "python app.py" to view the website.
6. If you run into any problems, refer back to [CS340_starter_flask_app](https://github.com/osu-cs340-ecampus/flask-starter-app) repository step 0. 

## Technologies & Languages
Flask

phpMyAdmin

Python 

HTML/CSS

## References 
This project was adapted using the template provided in the [CS340_starter_flask_app](https://github.com/osu-cs340-ecampus/flask-starter-app) repository.

Background image: [Game Wallpapers](https://www.gamewallpapers.com/index.php?titelpage=Hogwarts+Legacy&page=ultrawidegame).


