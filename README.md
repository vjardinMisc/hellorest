# kick off

    mkdir myfirst
    cd myfirst/
    mkdir -p src/HelloWorld
    vi src/HelloWorld/SayHello.php
    php -l src/HelloWorld/SayHello.php 
    composer init
    cat composer.json 
    vi composer.json 
    composer install
    mkdir tests
    vi tests/test.php
    php -l tests/test.php 
    php tests/test.php 
    vi .gitignore 
    git init
    git add .
    git commit -m "First commit"
    git remote add origin https://github.com/vjardinMisc/hellorest.git
    git push origin master

# redeploy

    composer require "vjardin/myfirst:dev-master"
    php vendor/vjardin/myfirst/tests/test.php
