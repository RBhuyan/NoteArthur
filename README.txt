A note-taking website written in Python, MySQL, HTML, CSS, Javascript, Jquery, and utilizing the Flask framework. The website features user login and storing the user information along with a dynamic search function. The website was created to demonstrate my knowledge of web devlopment, but the website itself is pretty useful to keep notes for myself. 


To run the app: set FLASK_APP=microblog.py    and then type in: flask run

To create the database:
    flask db init
    flask db migrate
    flask db upgrade

To interact with the database:
    flask shell

    u = User(username = 'rbhuyan1', email = 'hello')
    db.session.add(u)
    db.session.commit() #Makes permanent changes to the database

