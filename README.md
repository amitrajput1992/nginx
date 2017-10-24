# nginx

---
NGINX docker with pagespeed module, based on debian:jessie

---

To run
---

`docker run -d -p 80:80 -p 443:443 -v /home/nginx/conf.d:/etc/nginx/conf.d --name nginx nginx:latest`
