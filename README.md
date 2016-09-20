# Step-by-step-protocol-for-PHP-exercises-of-CodeLouisville

Please replace UserName as your own github user name
Excerise 3 "php-exercise-string-search" was used as the example here
 
1. fork
  * make sure log into github
  * goto "PHP Code Exercises" homepage: https://github.com/CodeLouisville/back-end-php/tree/master/exercises
  * click the link, go to the specific exercises homepage:https://github.com/CodeLouisville/php-exercise-string-search
  * click the "Fork" button at the up-right corner 

2. git clone
  * make new folder under C:\xampp\htdocs, and rename it as test3
  * start babun at that new folder: git clone https://github.com/UserName/php-exercise-string-search


3. Program accroding to the requirment of ReadMe
  * start xampp and start Apache
  * testing data at C:\xampp\htdocs\test3\php-exercise-string-search\tests\StringSearchTest.php
  * check the result at xammp page (if you echo the test result out):http://localhost/test3/php-exercise-string-search/src/string_search.php


4.  Runn Tests Locally
  * add the path of php.exe (Note: this only needs to be done once): export PATH=$PATH:"/cygdrive/C/xampp/php"
  * install composer (Note: this only needs to be done once): composer install
  * Run the tests: vendor/bin/phpunit

5. commit and push the solution to your fork
  * git add -A
  * git commit -m "tested locally"
  * git remote rm origin
  * git remote add origin https://github.com/UserName/php-exercise-string-search
  * git push -u origin master	(you need to type in username and password here)


6. create a pull request to pass the test remotely
  * go to your own exercise page: https://github.com/UserName/php-exercise-string-search
  * click the green button at the left of the page "New Pull Request"
  * click the green button at the left of the page "Create pull request"
  * click the green button at the right of the page "Create pull request"
  * wait until the test finished (~2min needed here)
  * it should show "All checks have passed"
