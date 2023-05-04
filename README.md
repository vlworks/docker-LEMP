# Nginx+PHP+MySql+phpMyAdmin

## 1. Git clone 
```bash
git clone https://github.com/vlworks/docker-LEMP.git
```
## 2. Create proxy
```bash
cd proxy/ && docker-compose up -d
```
## 3. Change virtual host for site and phpmyadmin
- nginx - VIRTUAL_HOST=site.local (line: 8)
- phpmyadmin - VIRTUAL_HOST=phpmyadmin.local (line: 40)
## 4. Composer up from root project folder
```bash
docker-compose up -d
```