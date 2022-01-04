1. We will need a file named hosts.ini, we will specify there IP of our target machine 
2. We will run commands as root by specifying "become: yes"
3. We also need some variables needed for DB.
4. Now we're gonna install the same pre-requirements and that is httpd, EPEL, PHP, MySQL, and maria DB
5. We also need to copy Mariadb.repo config file
6. We are ready to create DB for WordPress along with user with required privileges 
7. Now we are downloading WordPress and putting it in var/www
8. To work properly we need to specify and copy vhost.conf for apache and wp-config.php for WordPress
9. After restarting apache we should see WordPress hosted on our machine 

![alt text](https://github.com/OskarKozaczka/wordpress-ansible-automation/blob/main/wp.png?raw=true)
