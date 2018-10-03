# sym01
Symfony version basic 4.1.5.2

## 1
composer create-project symfony/website-skeleton sym01

## 2 .gitignore
add the hidden folders of files

##3 first commit 

git add .
git commit -m"first commit"
git remote add origin URL/GIT
git push origin master

##4 run server
php bin/console server:run

##5 creating README.md
Create the file README in GIT

##6 update libraries
$ composer update

##8 structure
Controller frontal: public/index.php
Controllers: src/Controllers
Models: src/Entity
Views: templates/

##9 file type best practice
yaml => configuration
Routing => annotations 
Datas => json or other

##10 add controller
$ php bin/console make:controller
Add MyFirstController to src/controller
Add my_first to templates

##11 view controller
Find the controller online. 
Check file the path error 404 => Routing
http://127.0.0.1:8000/my/first

