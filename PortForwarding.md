# Port Forwarding 
### nginx
To pull nginx
```bash
docker pull nginx
```
To forward nginx's port
```bash
docker run --name mynginx1 -p 80:80 -d nginx
```
---
### Kill nginx
```bash
docker kill mynginx1
```
---
### apache2
To pull apache2, ubuntu/apache2 is to be used
```bash
docker pull ubuntu/apache2
```
To forward apache2's port
```bash
docker run --name myapache2 -p 80:80 -d ubuntu/apache2
```
---
### Kill apache2
```bash
docker kill myapache2
```
