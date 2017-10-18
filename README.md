docker-carillon
===============

This is the specification for the Docker image to run a [carillon radio](https://github.com/fkmclane/carillon).


Usage
-----

```sh
$ curl -Ls https://gitcdn.link/repo/fkmclane/docker-carillon/master/run | sudo bash
```

Open `localhost:8080` and `localhost:8081` in your web browser.

Putting nginx with a certificate for `localhost:8080` and access controls for `localhost:8081` is recommended.
