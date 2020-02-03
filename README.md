# Recruitment-task

Requirements
--------------
- GIT instaled on server for clone repository with project
- Composer instaled on server to install the project
--------------
1. First make MySQL database on your server.

2. Choose the place where you want to put application on your server and execute this command to install the project:

    git clone https://PASTE_HERE_LINK_TO_REPOSITORY.html 
 
    cd Recruitment-task
 
    composer install
 
3. Create and migrate doctrine database:

    php bin/console doctrine:database:create
 
    php bin/console make:migration
 
    php bin/console doctrine:migrations:migrate
