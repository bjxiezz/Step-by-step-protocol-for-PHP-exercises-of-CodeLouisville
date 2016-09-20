# Step-by-step-protocol-for-PHP-exercises-of-CodeLouisville

* Please replace UserName as your own github user name. 
* Excerise 3 "php-exercise-string-search" was used as the example here
 
1. Fork
  * Make sure that you have logged into github
  * Goto "PHP Code Exercises" homepage: https://github.com/CodeLouisville/back-end-php/tree/master/exercises
  * Click the link, and Goto the specific exercises homepage:https://github.com/CodeLouisville/php-exercise-string-search
  * Click the "Fork" button close to the up-right corner of the page

2. git clone
  * Make a new folder under C:\xampp\htdocs, and rename it as "test3"
  * Start babun (a Windows shell) at that new folder 
  * Type the following command in the shell: git clone https://github.com/UserName/php-exercise-string-search


3. Programming accroding to the requirment of ReadMe
  * Start xampp and start Apache
  * Note: testing data is located at the folder C:\xampp\htdocs\test3\php-exercise-string-search\tests\StringSearchTest.php
  * Note: you can check the result at xammp page (if you echo the test result out): http://localhost/test3/php-exercise-string-search/src/string_search.php


4.  Runn Tests Locally (Type the following commands in the shell)
  * Add the path of php.exe (Note: this only needs to be done once): export PATH=$PATH:"/cygdrive/C/xampp/php"
  * Install composer (Note: this only needs to be done once): composer install
  * Run the tests: vendor/bin/phpunit

5. Commit and push the solution to your fork (Type the following commands in the shell)
  * git add -A
  * git commit -m "tested locally"
  * git remote rm origin
  * git remote add origin https://github.com/UserName/php-exercise-string-search
  * git push -u origin master	(you need to type in username and password here)


6. Create a pull request to pass the test remotely
  * Goto your own exercise page: https://github.com/UserName/php-exercise-string-search
  * Click the green button at the left of the page "New Pull Request"
  * Click the green button at the left of the page "Create pull request"
  * Click the green button at the right of the page "Create pull request"
  * Wait until the test finished (Normally, 1-5min is needed)
  * It should show "All checks have passed"
