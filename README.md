Python Flask app
----------------

# Run app
$ docker run -p 80:5000 aswadrangnekar/pyflask:custom

# build image:
$ docker build --tag pyflask .

# view images:
$ docker images

# prepare to push to docker hub
$ docker tag pyflask aswadrangnekar/pyflask:custom
$ docker push aswadrangnekar/pyflask:custom