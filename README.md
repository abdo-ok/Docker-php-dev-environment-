#My PHP development environment
  My local PHP development environment running on the top of xubuntu 14.04 LTS with docker & docker-compose .
### Web server :
  using nginx with simple conf file
### Data persistence layer :
  using MySQL
### PHP :
  using PHP fpm
### Additional PHP module :    
  You can add module by simply adding the following line to php/Dockerfile
```
RUN docker-php-ext-install module_that_you_want_to_install
```  
## MySQL administration :
  using phpMyAdmin
