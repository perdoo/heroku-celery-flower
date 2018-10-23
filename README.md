Deploy [Flower](https://github.com/mher/flower/) to Heroku to monitor [Celery](http://www.celeryproject.org/).

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

Configure the app by providing your broker url (RabbitMQ, Redis) and a username and password for logging into Flower. Please note that the database won't persist following a restart, since flower saves the state in a file using the http://docs.python.org/2/library/shelve.html format.
