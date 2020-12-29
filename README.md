###


https://www.digitalocean.com/community/tutorials/how-to-set-up-flask-with-mongodb-and-docker




docker exec -it mongodb bash

mongo -u mongodbuser -p




db.createUser({user: 'flaskuser', pwd: 'sua_senha_do_mongodb', roles: [{role: 'readWrite', db: 'flaskdb'}]})

mongo -u flaskuser -p sua_senha_do_mongodb --authenticationDatabase flaskdb



