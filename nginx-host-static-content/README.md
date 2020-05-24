## About
Hosting static content with nginx

```
$ docker run --name first-nginx -v $PWD:/usr/share/nginx/html:ro -d -p 8080:80 nginx
```

https://hub.docker.com/_/nginx
