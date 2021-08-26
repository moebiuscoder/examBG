# Nginx HTTP server and reverse proxy (nginx) S2I Sample Application

The application serves a single static html page via nginx.

To build and run the application:

```
$ s2i build https://github.com/moebiuscoder/examBG centos/nginx-116-centos7 demoBG
$ docker run -p 8080:8080 demoBG
$ # browse to http://localhost:8080
```