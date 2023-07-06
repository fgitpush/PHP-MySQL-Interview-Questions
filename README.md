
# PHP-Interview-Questions (+1000 Interview Questions)

> Click :star: if you like the project. Pull Request are highly appreciated.

### Table of Contents

| No. | Questions |
| --- | --------- |
|1  | [What are the pros of using Laravel?](#why-laravel) |
|2  | [What is inheritance in PHP?](#php-inheritance) |
|3  | [What is dependency manager?](#what-is-dependency-manager) |
|4  | [You have an array of colors('red', 'blue', 'green' ,..., n) and an array of data with x elements where x > n. Print the data array in such a manner that each row would have alternating color and when the color index ends, start from the first color again until the data arrays iterations end.](#what-is-api-php) |
|5  | [What is Method Overriding?](#what-is-channels-php) |
|6  | [What is Overloading?](#what-is-console-php) |
|7  | [What are Abstract classes?](#what-is-controller) |
|8  | [What are Interfaces?](#what-are-views) |
|9  | [What are Access Modifiers?](#what-is-a-model) |
|10  | [What is OOP parent child relationship?](#what-is-request-response) |
|11  | [When are Magic methods?](#what-are-migrations) |
|12  | [What are Traits?](#what-are-seeders) |
|13  | [What are php globals?](#what-are-service-providers) |
|14  | [What is REST?](#what-is-middleware) |
|15 | [How will you increase security in a Contact form using PHP?](#what-is-orm) |
|16 | [Send a mail with attachment using phpmailer](#what-is-eloquent) |
|17 | [Did you worked on payment gateway?](#what-is-query-builder)
|18 | [List the HTTP methods in PHP](#what-are-facades) |
|19 | [Write a function to Reverse a string](#what-is-repository-pattern) |
|20 | [Write a function to sort an array in ascending order](#What-is-Authentication-using-Passport-CSRF-XSRF) |
|21 | [What is Binary Search](#what-is-unit-testing) |
|22 | [How can we access the data sent through the URL with the GET method?](#what-is-caching) |
|23 | [Write array element count without using count variable?](#how-to-setup-emails) |
|24 | [Write a function for string reverse without using php functions](#what-are-queues) |
|25 | [What is NULL?](#what-are-jobs)
|26 | [Draw a Pyramid](#what-are-advanced-eloquent-and-query-builder) |
|27 | [One ring bells at 20 sec, second will 40 sec and third will 60.at what time these three will ring together?](#which-is-error-management) |
|28 | [Get the last thee max salaried person from table via sql](#how-to-create-an-api) |
|29 | [What is multi-threading?](#what-are-events) |
|30 | [Does PHP support multithreading?](#what-are-listeners) |
|31 | [Write the code of upload a file in php?](#what-are-payments-and-cashier) |
|32 | [What is difference between echo and print?](#what-is-test-driven-development) |
|33 | [Cut round cake in 8 pieces using 3 straight lines, draw on paper](#what-is-package-development) |
|34 | [What is indexing?](#what-are-laravel-scout-search-and-algolia) |
|35 | [If you are in the race and you crossed the 2nd person in the race then what is your position?](#what-is-socialite-auth) |
|36 | [Display sum of 1 to N numbers without loop](#what-is-vue-js) |
|37 | [Write code to display a square with ' * '](#How-to-connect-Laravel-with-other-SQL-databases) |
|38 | [Write joins?](#How-to-connect-Laravel-with-non-SQL-databases) |
|39 | [Write unions?](#what-is-lumen) |
|40 | [Wrie a function to print Fibonacci series?](#what-is-redis) |
|41 | [How to get the data from more than 3 table without use join ?](#what-is-memcache) |
|42 | [What is the difference between group by and order by?](#What-is-Horizontal-scaling) |
|43 | [Difference between curl and ajax?](#What-is-Vertical-scaling) |
|44 | [How to do error handling in PHP?](#What--Single-Page-Application-in-Laravel) |
|45 | [What is PEAR?](#What-are-Microservices-in-Laravel) |
|46 | [What is CSRF and JWT token?](#what-is-CSRF-and-JWT-token) |
|47 | [How to get the data from more than 3 table without using a join?](#what-is-soa) |
|48 | [What are validations and custom validations?](#what-are-validators) |
|49 | [How to fetch last two records from the table?](#what-is-composer) |
|50 | [Print 1 to 100 no divide by 3 and 5](#what-is-symfony) |
|51 | [Who is the father of php?](#what-is-route-caching) |
|52 | [Explain caching and its ways?](#default-packages) |
|53 | [How to call CURL?](#what-are-named-routes) |
|54 | [What are the new trends in PHP](#what-is-dependency-injection) |
|55 | [Form validation using jquery](#what-are-contracts) |
|56 | [Create a project with CRUD, one algorithm logic and insert data in db for testing?](#what-is-query-log) |
|57 | [Mysql Engines](#what-are-laravel-traits) |
|58 | [What is I in mysqli?](#what-are-Bundles-in-Laravel) |
|59 | [Query to get the 31st highest salary](#what-are-system-requirements-for-laravel) |
|60 | [How can we style to html document in different ways ?](#what-are-aggregate-methods-in-query-builder) |
|61 | [What is MVC architecture?](#what-is-singelton-design-pattern) |
|62 | [Latest version for PHP and Bootstrap? ](#what-is-reverse-routing) | 
|63 | [Did you worked on payment gateway ?](#what-are-Popular-composer-packages) |
|64 | [Replace the integer value of 2 variables without creating the third?](#how-to-get-the-data-from-more-than-3-table-without-using-a-join) |
|65 | [Namespaces?](#list-some-artisan-commands) |
|66 | [Name some array functions](#what-are-sessions) |
|67 | [What is SQl Injection?](#what-are-cookies) |
|68 | [aaaaaaaaaaaaaaaaaaa](#what-is-current-version-of-PHP-MySQL-Laravel-MongoDB-etc) |
|69 | [Describe design architecture of an app?](#Describe-design-architecture-of-an-app) |
|70 | [What are SQL Injections?](#What-are-SQL-Injections) |
|71 | [How SQL injection can be prevented?](#How-to-call-static-methods) |
|72 | [What is DOM?](#How-to-achieve-multiple-DB-hosts)
|73 | [What is cross site scripting and how it can be prevented?](#what-is-Abstract-class) |
|74 | [What is Restful Webservice?](#what-are-Default-ports-for-MySQL-Email-etc) |
|75 | [How delete operation can be performed using Restful webservice?](#Explain-Joins) |
|76 | [Explain Unions](#Explain-Unions) |
|77 | [Write a program for all the number from 1 to 100 ,all the number that are divisble by 3 print 'FIZZ' ,all those number divisible by 5 print 'BUZZ' for thoose number divisible by both 3 and 5 print 'FIZZBUZZ' for other print the number itself (just find the mod and use if loop)](#How-mongodb-is-better-than-relational-databases) |
|78 | [Sorting of array in ascending order ?](#What-is-mongodb) |
|79 | [What is the need of interface?](#What-is-default-session-time)
|80 | [How to add aws plugin in PHP?](#How-to-create-hooks-in-Laravel) |
|81 | [How to reduce http request on page loading?](#What-is-csrf-token-and-xss-attack) |
|82 | [Constraints and triggers](#Select-highest-and-nth-highest-salary-from-DB) |
|83 | [Write a join](#Write-a-join) |
|84 | [Write a union](#Write-a-union) |
|85 | [Design pattern](#Write-a-complex-query) |
|86 | [How can we access the data sent through the URL with the GET method ?](#Explain-an-apps-DB-architecture) |
|87 | [How to find datatype of $i ?](#What-is-Difference-between-PHP-5-and-4) |
|88 | [What is the session and cookies and difference between in it](#What-is-the-difference-among-various-php-versions) |
|89 | [What is the difference among various mysql versions?](#What-is-the-difference-among-various-mysql-versions) |
|90 | [What is the difference among various Laravel versions?](#What-is-the-difference-among-various-Laravel-versions) |
|91 | [How to add AWS plugin in PHP?](#How-to-add-AWS-plugin-in-PHP) |
|92 | [What are design patterns?](#What-are-design-patterns) |
|93 | [What is the difference between GET and POST](#What-is-the-difference-between-GET-and-POST) |
|94 | [Which is fast between GET and POST?](#Which-is-fast-between-GET-and-POST) |
|95 | [Write array element count without using count variable.](#Explain-4-basics-of-OOP) |
|96 | [Difference between mysiam and innodb storage engine](#What-is-diference-between-abstract-class-and-interface) |
|97 | [HTTP methods in PHP](#What-is-MVC-Framework) |
|98 | [String reverce without using php functions](#Write-CRUD-in-Laravel-Eloquent) |
|99 | [Zend Framework](#Explain-CURL-and-SOAP) |
|100 | [How to declare an array in php?](#In-MySql-we-use-many-types-of-engines-which-one-is-faster-and-why) |
|101 | [What are the encryption techniques in PHP?](#What-are-Triggers) |
|102 | [A ladder of 10 feet is hanging from the side of a boat. 2 feet of the ladder is underwater. If a tide of 5m height comes, how much of the ladder will be submerged?](#What-are-Procedures) |
|103 | [How to achieve multiple DB Hosts in PHP Laravel application?](#What-are-some-new-feaatures-of-Laravel-X) |
|104 | [How can protect my site from world class hackers ?](#how-to-combine-multiple-inline-style-objects) |
|105| [Variable name of max execution time constant in php?](#Explain-Difference-between-session-and-cookies)
|106| [what is HTML DOM?](#Merge-2-arrays-with-duplicate) |
|107| [You have the following tables: Student(Id, name), Course(Id, name), result (st_id, c_id, grade ). Display Student name, no of Courses in which the student has failed, the failed grade being F.](#Find-the-count-of-vowel-and-consonants) |
|108| [Explain AWS Services](#Explain-AWS-Services) |
|109| [How to do Web scraping?](#How-to-do-Web-scraping) |
|110| [Explain require and require once difference](#Explain-require-and-require-once-difference) |
|111| [Explain include and require diffrence](#Explain-include-and-require-diffrence) |
|112| [What kind of Debugger you are familiar with ?](#Directory-structure-of-Laravel) |
|113| [How to sort arrays in descending order?](#How-to-install-Laravel-via-composer) |
|114| [What is the default SSL port?](#Which-ORM-are-being-used-by-laravel) |
|115| [There is an array with some elements and find out second max element of an array without using any built in function?](#List-types-of-relationships-available-in-Laravel-Eloquent) |
|116| [How you can assign the value to a HTML input element using jquery?](#How-to-enable-maintenance-mode-in-Laravel) |
|117| [How you can read a HTML element value using j query?](#What-is-the-purpose-of-using-dd()-function-in-laravel) |
|118| [Ways to print an array?](#How-do-you-register-a-Service-Provider) |
|119| [What is recursion?](#Explain-Laravel-framework-Architecture) |
|120| [How many types of CSS inclusion methods?](#Helper-Functions) |
|121| [Remove Duplicates rows from table](#What-is-Fillable-Attribute-in-a-Laravel-Model) |
|122| [Code for finding two numbers in an array in which the sum of them will be equal to some static variable value which was already defined](#What-is-Guarded-Attribute-in-a-Laravel-Model) |
|123| [There are 8 coins of 1 gram each and there is a coin of 4 grams. How would you easily find that 1 overweighted coin ? ](#What-are-Closures-in-Laravel) |
|124| [How to create a session?](#How-to-get-Logged-in-user-info-in-Laravel) |
|125| [How to set a value in session ?](#What-is-Laravel--Elixir) |
|126| [How to Remove data from a session?](#What-is-Laravel-Mix) |
|127| [Have you ever handle one million user inputs in a second ?](#How-can-you-display-HTML-with-Blade-in-Laravel) |
|128| [Write down syntax for ajax call ?](#List-out-databases-that-laravel-supports) |
|129| [Find a string character count without using string functions ?](#How-to-use-custom-table-in-Laravel-Model) |
|130| [Run time and compile time polymorphism](#How-To-Use-Select-Query-In-Laravel-Eloquent-and-QB) |
|131| [How to reverse the position of words in the string](#What-are-Accessors-and-Mutators-in-Eloquent-and-why-should-you-use-them) |
|132| [Will session variables work if I disable cookies?](#How-do-I-log-an-error) |
|133| [How to optimize database?](#What-is-Monolog-library-in-Laravel) |
|134| [There is array of 1 million integers (numbers can be repeatative). find smallest and largest number.](#Exceptions-are-handled-by-which-class-in-Laravel) |
|135| [Solve the rubiks cube](#What-is-Serialization-in-Laravel) |
|136| [What are different types of errors in PHP](#What-is-Response-in-Laravel) |
|137| [How to delete a specific element in an array?](#What-is-Response-Macros-in-Laravel) |
|138| [How to get the record with maximum mark of a student from a table ?](#What-is-Rate-Limiting-OR-Throttle-in-Laravel) |
|139| [Find names of students whose age is greater than 21?](#What-is-Lazy-vs-Eager-Loading-in-Laravel) |
|140| [What is Redis?](#How-to-get-current-environment-in-Laravel) |
|141| [What is Memcache?](#How-to-use-custom-table-in-Laravel-Model) |
|142| [Do you know how to write commands in Linux/Ubuntu?](#What-is-Binding) |
|143| [How to create an API?](#Explain-Binding-A-Singleton) |
|144| [what is default session time](#Explain-Binding-Instances) |
|145| [Do JS validation?](#Explain-Binding-Primitives) |
|146| [What is an Associate array?](#Explain-Contextual-Binding-and-how-does-it-work) |
|147| [How will you generate random numbers using PHP?](#What-is-Tagging) |
|148| [Difference between array merge and array combine?](#Explain-Extending-Bindings) |
|149| [Finding 5th child in jQuery](#What-is-the-make-Method) |
|150| [Compiletime and runtime polymorphism and what is virtual function?](#How-to-clear-cache-in-Laravel) |
|151| [Update and insert in sql?](#What-is-CSRF-token) |
|153| [Write basic sql queries](#How-will-you-explain-homestead-in-Laravel) |
|154| [Find if pair exist in array whose sum is k?](#How-can-we-get-the-user's-IP-address-in-Laravel) |
|155| [Check if string is palindrome?](#How-will-you-create-a-helper-file-in-Laravel) |
|156| [What is 2 tier and 3 tier architecture?](#How-can-we-create-a-record-in-Laravel-using-eloquent) |
|157| [How can we get the user's IP address in PHP?](#give-a-simple-example-of-jest-test-case) |
|158| [Why should we use RDBMS or whaat was challanges with traditional file systems?](#What-is-faker-in-Laravel) |
|159| [Difference between array combine and array merge?](#What-are-active-records) |
|160| [Preg_replace?](#What-are-the-difference-between-insert-and-insertGetId-in-laravel) |
|161| [REST VS AJAX](#Talk-about-Laravel-Vapor-Compatibility) |
|162| [REST VS SOAP](#What-is-Semantic-Versioning) |
|163| [Sort a array with predefined function](#What-are-Jobs-and-Middleware) |
|164| [Create a class and call add and subtract function](#talk-about-Laravel-User-Interface-(UI)) |
|165| [Why this error occur header already sent](#Talk-about-Eloquent-Subquery-Enhancements) |
|166| [Difference between put and post?](#What-are-improved-Authorization-Responses) |
|167| [What is final class?](#What-are-lazy-collections) |
|168| [How to implement Security in app?](#How-to-make-a-constant-and-use-globally) |
|169| [What is layers in mysql?](#How-to-remove-public-from-URL-in-laravel) |
|170| [What is master and slave in db?](#What-are-the-difference-between-soft-delete-&-delete-in-Laravel) |
|171| [Do you know how to write server commands?](#How-we-can-upload-files-in-laravel) |
|172| [What is stack?](#How-to-create-real-time-sitemap.xml-file-in-Laravel) |
|173| [What is queue?](#How-to-use-skip()-and-take()-in-Laravel-Query) |
|174| [What is Linkedlist?](#What-is-tinker-in-laravel) |
|175| [How to declare an array? ](#What-is-a-REPL) |
|176| [Find the square numbers in the given range (x,y).](#How-to-use-multiple-'OR'-condition-in-Laravel-Query) |
|177| [What are datatypes in mysql?](#Please-write-some-additional-where-Clauses-in-Laravel) |
|178| [Write a program to print prime number between 499 and 699](#How-to-check-column-is-exists-or-not-in-a-tabl-using-Laravel) |
|179| [Singleton Class and Trait and show use of Trait by Creating Singleton Class?](#What-is-eager-loading-in-Laravel) |
|180| [Difference between $var and $$var?](#How-to-generate-application-key-in-laravel) |
|181| [Insert data in three table in a single query](#What-is-LTS-version-of-Laravel) |
|182| [What is JWT token?](#How-to-use-GROUP_CONCAT()-with-JOIN-in-Laravel) |
|183| [How to do Api security?](#How-to-extend-login-expire-time-in-Auth) |
|184| [Find min and max from array of 1 million](#How-to-extend-a-layout-file-in-laravel-view) |
|185| [Write a logic to validate email id using javascript?](#How-do-you-use-yield()) |
|186| [What is searialization?](#How-to-redirect-form-controller-to-view-file-in-laravel) |
|187| [You have 2 php pages. (lib.php and welcome.php) u have to use a variable (say x) from lib.php in welcome.php. if u change the x in welcome.php it shouldnt affect the value in lib.php?](#How-to-get-current-route-name) |
|188| [Use of CORS in api development?](#What-is-ACL-in-laravel) |
|189| [How to concatenate two variables in PHP?](#How-to-check-Ajax-request-in-Laravel) |
|190| [Program for Anagram?](#How-to-check-if-value-is-sent-in-request) |
|191| [What is composer?](#Laravel-String-Helper-functions) |
|192| [What does var_dump() function does in PHP?](#Laravel-Array-Helper-functions) |
|193| [Write a program for chessboard?](#How-to-exclude-a-route-with-parameters-from-CSRF-verification) |
|194| [Preventing XSS attacks](#What-are-policies-classes) |
|195| [What is web clustering?](#How-to-rollback-last-migration) |
|196| [Difference between primary key and unique key ? ](#What-do-you-mean-by-Laravel-Dusk) |
|197| [What is Psr standard?](#Explain-Laravel-echo) |
|198| [Print Floyd's triangle in php.](#What-is-namespace-in-Laravel) |
|199| [Pass by value functions and call by address](#What-is-Laravel-Forge) |
|200| [Check duplicates in a array?](#State-the-difference-between-CodeIgniter-and-Laravel) |
|201| [Check give number is arm strong number or not?](#What-is-an-Observer) |
|202| [Write a program to find the angle between the hands of a clock](#What-is-the-use-of-the-bootstrap-directory) |
|203| [Program to find permutation of string](#What-is-the-default-session-timeout-duration) |
|204| [Is there any difference between mysql_connect() and mysql_pconnect() ?](#Explain-API.PHP-route) |
|205| [Explain Triggers](#Define-hashing-in-Laravel) |
|206| [What are Stored Procedures?](#What-is-Localization) |
|207| [Explain Events](#Explain-the-concept-of-encryption-and-decryption-in-Laravel) |
|208| [Write self join query](#How-to-share-data-with-views) |
|209| [Different between having and where in SQL query](#How-to-generate-a-request-in-Laravel) |
|210| [What is PDO?](#I-just-have-installed-a-fresh-version-of-Laravel-5-and-I-have-the-white-screen-of-death-What’s-wrong) |
|211| [Union VS union ALL and can we use group by in unions?](#How-to-assign-a-variable-value-for-all-view-file) |
|212| [What is the difference between left joint and right joint?](#How-to-make-a-constant-and-use-globally) |
|213| [What is the difference between == and === ?](#How-to-check-current-installed-version-of-Laravel) |
|214| [How mongodb is better than relational databases?](#What-does-composer-dump-autoload-do) |
|215| [Difference between constructor or distructor in php?](#What-is-Kept-in-vendor-directory-of-Laravel) |
|216| [Revert a linked list using recursion](#What-does-PHP-compact-function-do) |
|217| [What is PEAR in PHP?](#What-is-APP_KEY-used-for) |
|218| [Explain the difference b/w static and dynamic websites?](#What-is-APP_KEY-used-for) |
|219| [What is the name of scripting engine in PHP?](#What-is-APP_KEY-used-for) |
|220| [Explain the difference between PHP4 and PHP5?](#What-is-APP_KEY-used-for) |
|221| [What are the popular frameworks in PHP?](#What-is-APP_KEY-used-for) |
|222| [What is the use of count() function in PHP](#What-is-APP_KEY-used-for) |
|223| [Which programming language does PHP resemble to?](#What-is-APP_KEY-used-for) |
|224| [List some of the features of PHP7](#What-is-APP_KEY-used-for) |
|225| [List some of the features of PHP5](#What-is-APP_KEY-used-for) |
|226| [List some of the features of PHP6](#What-is-APP_KEY-used-for) |
|227| [What is the difference between "echo" and "print" in PHP?](#What-is-APP_KEY-used-for) |
|228| [What is the difference between $message and $$message?](#What-is-APP_KEY-used-for) |
|229| [What are the ways to define a constant in PHP?](#What-is-APP_KEY-used-for) |
|230| [What are magic constants in PHP?](#What-is-APP_KEY-used-for) |
|231| [How many data types are there in PHP?](#What-is-APP_KEY-used-for) |
|232| [How to do single and multi line comment in PHP?](#What-is-APP_KEY-used-for) |
|233| [Explain PHP parameterized functions](#What-is-APP_KEY-used-for) |
|233| [How many types of array are there in PHP?](#What-is-APP_KEY-used-for) |
|234| [What is the difference between indexed and associative array?](#What-is-APP_KEY-used-for) |
|235| [How to get the length of string?](#What-is-APP_KEY-used-for) |
|236| [Explain setcookie() function in PHP?](#What-is-APP_KEY-used-for) |
|237| [How can you retrieve a cookie value?](#What-is-APP_KEY-used-for) |
|238| [What is a session?](#What-is-APP_KEY-used-for) |
|239| [What is the difference between session and cookie?](#What-is-APP_KEY-used-for) |
|240| [What is PHP session_start() and session_destroy() function?](#What-is-APP_KEY-used-for) |
|241| [What is the method to execute a PHP script from the command line?](#What-is-APP_KEY-used-for) |
|242| [How to create connection in PHP?](#What-is-APP_KEY-used-for) |
|243| [How can we increase execution time of a PHP script?](#What-is-APP_KEY-used-for) |
|244| [What are the different types of errors in PHP?](#What-is-APP_KEY-used-for) |
|245| [What are the encryption functions in PHP?](#What-is-APP_KEY-used-for) |
|246| [What is htaccess in PHP?](#What-is-APP_KEY-used-for) |
|247| [You have the following tables: Student(Id, name), Course(Id, name), result (st_id, c_id, grade ). Display Student name, no of Courses in which the student has failed, the failed grade being F.](#What-is-APP_KEY-used-for) |
|248| [How will I increase security in a Contact form using PHP?](#What-is-APP_KEY-used-for) |
|249| If i know what is ACID?|
||different raid systems|
||If a parent record was accidentally deleted without removing the child records, what query could you use to determine what records were "orphaned".|
||list Background Processes in oracle Database|
||Regarding Replication, deadlock, installation, upgradation|
||Q. What is PHP?|
||Q. Is PHP case sensitive?|
||Q. Is PHP weakly typed language?|
||Q. How do we install PHP?|
||Q. What is Composer?|
||Q. How to check current PHP version and other information about our system?|
||Q. What is interpreter?|
||Q. Is PHP compiled or interpreted?|
||Q. Explain datatypes in PHP?|
||Q. What are rules for naming a variable?|
||Q. How will you define a constant?|
||Q. What is the purpose of constant() function?|
||Q. What are the differences between constants and variables?|
||Q. What are the different scopes of variables?|
||Q. What is string?|
||Q. What is the difference between single quoted string and double quoted string?|
||Q. How can you convert string into array elements?|
||Q. How can you convert array into strings?|
||Q. How can you concatenate two or more strings?|
||Q. Differentiate between echo and print()?|
||Q. Explain static variables?|
||Q. What are PHP magic constants?|
||Q. Why do we need trim() function?|
||Q. Can you count the number of words in a string?|
||Q. How to reverse a string?|
||Q. How to find the position of a specific text in a string?|
||Q. How can you change cases in a string?|
||Q. Can you replace a substring?|
||Q. Differentiate between str_replace() and str_ireplace()?|
||Q. Differentiate between printf() and print()?|
||Q. Differentiate between strstr() & strchr() functions?|
||Q. Differentiate between strstr() and stristr()?|
||Q. Can you encode a string in PHP?|
||Q. Differentiate between strcmp() and strncmp()?|
||Q. Is it possible to remove the HTML tags from data?|
||Q. What is the use of gettype() in PHP?|
||Q. What is heredoc and nowdoc?|
||Q. Explain if-else statement?|
||Q. Explain switch statement with example?|
||Q. Differentiate between switch and if-else statement?|
||Q. What are the different types of operators?|
||Q. Explain arithmetic operators?|
||Q. Explain the assignment operators?|
||Q. Explain the logical operators?|
||Q. Explain the unary operators?|
||Q. Explain the comparison operators?|
||Q. Differentiate between === and == operators in PHP?|
||Q. Explain pre and post increment with example?|
||Q. What do you mean by operator overloading?|
||Q. How many loops are available in PHP?|
||Q. Explain while loop with example?|
||Q. Explain do-while loop with example?|
||Q. Explain for loop with example?|
||Q. Explain foreach loop with example?|
||Q. How can you implement an infinite loop in PHP?|
||Q. How can you implement recursion in PHP?
||Q. Explain break statement with example?
||Q. Explain continue statement with example?
||Q. Give example of declaration in php?
||Q. What is require in PHP?
||Q. What is an array?
||Q. How can you print an array in PHP?
||Q. What do we mean by the base address of an array?
||Q. What do we mean by keys and values?
||Q. What are the keys & values in an indexed array?
||Q. How can we convert array into string?
||Q. How can we convert a string into an array elements?
||Q. How can we concatenate arrays in PHP?
||Q. Which function counts all the values of an array?
||Q. How can we check if an element exists in an array?
||Q. Which function inserts an element to the end of an array?
||Q. What is the use of array_chunk() function?
||Q. Why do we use extract()?
||Q. What is a function?
||Q. What are the different types of functions?
||Q. Classify function on basis of parameters?
||Q. Differentiate between parameterized and non parameterized functions?
||Q. Does PHP support both call by value and call by reference?
||Q. Explain call by value?
||Q. Explain call by reference?
||Q. What are the function declaration rules?
||Q. How can we declare user defined functions?
||Q. What do we mean by actual and formal parameters?
||Q. Maximum how many arguments are allowed in a function in PHP?
||Q. Explain header()?
||Q. What do we mean by return type of a function?
||Q. What is the return type of a function that doesn't return anything?
||Q. Do we need to mention the return type of a function explicitly in PHP?
||Q. What is function that can be used to build a function that accepts any number of arguments?
||Q. Explain the return statement?
||Q. Can we use multiple return statements in a function?
||Q. What is the use of ini_set()?
||Q. What is the difference between unlink and unset functions?
||Q. How ereg() function works?
||Q. How eregi() function works?
||Q. What is the purpose of getdate() function?
||Q. What is the purpose of date() function?
||Q. How will you call member functions of a class?
||Q. How can we display the correct URL of the current webpage?
||Q. How to get the information about the uploaded file in the receiving script?
||Q. What do we mean by server?
||Q. What are PHP superglobals?
||Q. How will we get information sent via GET method?
||Q. How will you get information sent via POST method?
||Q. What is the purpse $_REQUEST variable?
||Q. What is the purpose of $_FILES variable?
||Q. What is the purpose of $GLOBALS variable in PHP?
||Q. What is the purpose of $_SERVER variable in PHP?
||Q. What is the purpose of $_COOKIE variable in PHP?
||Q. What do you mean by environment variable in PHP?
||Q. What is the purpose of $_ENV variable in PHP?
||Q. What is the purpose of $_SESSION variable in PHP?
||Q. How will you redirect a page?
||Q. What is the purpose $_PHP_SELF variable?
||Q. How will you get the browser details using PHP?
||Q. What do you mean by HTTP status codes?
||Q. What are the HTTP client error codes?
||Q. What are the informational status codes?
||Q. What are the HTTP success codes?
||Q. How do you get the redirection related information?
||Q. What is API?
||Q. What is REST API?
||Q. What is JSON?
||Q. Why do we need JSON?
||Q. How can you exchange data using JSON?
||Q. Differentiate between JSON & XML?
||Q. What are the advantages of JSON?
||Q. What is Session?
||Q. What is Cookie?
||Q. Differentiate between Session & Cookie?
||Q. How do we start a session?
||Q. How can we set session variable?
||Q. How to remove value from session variable?
||Q. When do we need to set session variables?
||Q. When do we need a session and not a cookie?
||Q. When do we need a cookie and not a session?
||Q. How can we set a cookie?
||Q. How to modify a cookie value?
||Q. How will we make a check that a cookie is set or not?
||Q. How to retrieve all cookie values?
||Q. How to delete a cookie?
||Q. How can we implement 'remember me' using PHP?
||Q. Classify cookies?
||Q. How will you delete a cookie?
||Q. How to track login and logout using PHP?
||Q. How to create a file?
||Q. What are the other way to write in a file?
Q. How will you check if a file exists or not using php?
Q. How to delete a file?
Q. How to copy a file?
Q. How to rename file?
Q. How to check whether a file or directory exists?
Q. How to check path of the file in PHP?
Q. How to check size of the file in PHP?
Q. How to write the contents inside file?
Q. Explain file() method?
Q. How To change the file permissions?
Q. What are different ways to get the extension of a file?
Q. How to create a directory using PHP?
Q. How to get files(contents) from directory?
Q. How to open a directory?
Q. What is include in php?
Q. What is require_once in php?
Q. What is include_once in php?
Q. What is require() in PHP?
Q. What is difference between require and include?
Q. What is RegEx?
Q. Why do we need RegEx?
Q. How preg_match() function works?
Q. Regualar Expression Notations?
Q. Regualar Expression Examples?
Q. What is OOPs?
Q. What is an object?
Q. How can we create object of a class?
Q. What is a class?
Q. What are the basic features of OOPs?
Q. Is PHP purely an object oriented language?
Q. Differentiate between OOPs & POPs?
Q. What is generalization?
Q. What is specialization?
Q. What is aggregation?
Q. What is composition?
Q. What is association?
Q. What is abstraction?
Q. What is encapsulation?
Q. What is inheritance?
Q. What is super class?
Q. What is a sub class?
Q. How can you inherit a class in PHP?
Q. What is a constructor?
Q. Explain __construct()?
Q. Classify constructor?
Q. What is a destructor?
Q. Explain $this?
Q. Explain multiple inheritance?
Q. Does PHP support multiple inheritance?
Q. Explain multi-level inheritance?
Q. What is polymorphism?
Q. What is method overloading?
Q. Does PHP support method overloading?
Q. What is method overriding?
Q. What are interfaces in PHP?
Q. What does the presence of operator ‘::’ represent?
Q. How to define a class in PHP?
Q. How will you add a constructor function to a PHP class?
Q. How will you add a destructor function to a PHP class?

Q. How will you access the reference to same object within the object in PHP?
Q. What do you mean by access modifier?
Q. Explain access modifiers in PHP?
Q. Explain final class in PHP?
Q. Explain abstract class?
Q. What is interface?
Q. What do you mean by an exception?
Q. Define Exception class Hierarchy?
Q. How do we handle exceptions?
Q. Differentiate between exception and error?
Q. What do we mean by error log?
Q. How do we see PHP errors?
Q. What are the exception class functions?
Q. What does the expression Exception::__toString means?
Q. Why do we need cryptography?
Q. What do we mean by hash functions?
Q. Whart is hash function in PHP?
Q. Example using hash()?
Q. What is encoding and decoding?
Q. What is SHA1?
Q. Can sha1 be decrypted?
Q. What is sha1_file()?
Q. What are the disadvantages of sha1()?
Q. What MD5 means?
Q. Why can not a MD5 hash be decrypted?
Q. Is md5 reversible?
Q. Compare sha1() and md5()?
Q. What is enctype?
Q. Explain each Mcrypt function supported in PHP?
Q. What is cryptography authentication?
Q. What is HTML?
Q. Differentiate between PHP and HTML?
Q. What are the different methods or HTTP verbs of sending data to the server?
Q. What is the difference between GET and POST methods?
Q. How can we send email?
Q. How file upload works?
Q. What is SQL?
Q. How many types of database connections possible in PHP?
Q. Adavantages of PDO over MySQLi approach?
Q. How connect to the database using PDO?
Q. What is SQL injection?
Q. How can we get the browser's details using PHP?
Q. What is the use of Xdebug extension?
Q. What is the purpose of php.ini file?
Q. What is curl?
Q. What is PDO in PHP?
Q. What is autoloading classes in PHP?
Q. Discuss die()?
Q. What are variable variable?
Q. What are return type declarations?
Q. Explain the Exception Hierarchy introduced in PHP 7?
Q. What is use of Spaceship Operator?
Q. After the code below is run, what are the values of $a and $b?
Q. Looking at the code below, what will the function getTemplateName() return?
Q. Explain, line by line, what the following code does. Can it be improved?
Q. What is use of Null Coalesce Operator?
1. Q1. Draw star pattern like. n=1. * n=2. ** * n=3. *** ** * n=4 **** *** ** * n=5. ***** **** *** ** *  
2. Given an array of numbers [1,3,3,5,9,4,1,10,9,7,2,7], Write a php function that will print numbers that are not duplicated in array. [5,4,10,2]
3. First round is pattern based question like.. n=1 n=2 n=3 * * * *** *** *** * * * * ***** ***** * * * *******
4. Whats the angle between the minute pointer and hour pointer at 3:15
5. Draw a reversed T pattern which would generate on dynamic series by giving odd input * * * * * @ @ @ @ Second Question is : * * * * * *
6. Get the last thee max salaried person from table via sql.
7. I was having 8 Yrs of experience but they asked me how to access array elements
8. 12: one ring bells at 20 sec, second will 40 sec and third will 60.at what time these three will ring together?
9. Tell me about yourself. What technologies you learnd?
10. 1.hr interview-they check your verbal and written communication ability 2.written test consists of 10 questions with mix of javascript and php 3.technical test - here they ask you to install LAMP ,Wordpress, Virtualization and/or FTP
11. Web Services (how have you used them).
12. About the learning curve - are you ready to lean & deliver
13. It was an assessment, so basic questions on PHP/MySQL.
14. How much did you make at each of your previous roles?
15. What is PHP
16. What's your favorite text editor?
17. Where we put the business logic in the MVC Design Pattern ?
18. 1) Tell me about yourself?? 2) write a note on a topic which is not related to technology??
19. Only Time Pass. Not Required the PHP developer. How to load the website quickly in mysql.
20. what is mvc?
21. how do you swap two variables without using temporary variable
22. Convert str to array in php
23. Convert array to str in php
24. What is difference between echo and print
25.  Write the code of upload a file in php.
26. Code in php a Checkerboard 5x5 and output it into html
27. What is Php?
28. cut round cake in 8 pieces using 3 straight lines, draw on paper
29. Tell me about static variables
30. create a web page and connecting it to database
31. 1. Display sum of 1 to N numbers 2. Display 1-100 numbers in each line where if it is divisible by 3 then '***' if by 5 then '***' 3. Write code to display a square with ' * '
32. If you are in the race and you crossed the 2nd person in the race then what is your position?
33. Sample streamed data Please write a program stream-sampler that receives and processes an input stream consisting of single characters.
34. Consider generating a monthly mobile bill for data usage. A basic charge of Rs. 200 allows for 20GB of data per month, with a daily cap of 2GB. The user has to pay Rs. 200 per month irrespective of the amount of data used. For each additional MB used above 2GB per day, the user is to pay an additional Rs. 0.025. Also, for each additional MB above 20GB for the whole month, the user needs to pay an additional Rs. 0.05. Assumption: 1GB = 1024MB Write a function that does the following: - Accepts an array containing daily usages in MB for a month - Calculate the total monthly bill for the input, including the additional charge for exceeding daily and monthly limits, if any. Sample Input/Output Input Data usage: date of month => data used in MB Array ( [2] => 3000 [5] => 1250 [10] => 2000 [12] => 300 [14] => 900 [16] => 4250 [18] => 2560 [19] => 1500 [22] => 190 [26] => 2020 [28] => 5050 ) Output Array ( [baseCharge] => Rs. 200 [dailyAdditional] => Rs. 166.7 [monthlyAdditional] => Rs. 127 [totalBill] => Rs. 493.7 )
35. SQL: you have a table with customers, with gender m and f. Write a query to update m with f, f with m in a single query, without temporary tables
36. how can you display 3rd highest salary from database? 
37.  how can you handle errors in php?
38. how to send a http request in php?
39. In depth concepts of OOPS.
40. How will I increase security in a Contact form using PHP
41. difference between sleep and wakeup?
42. difference between include and require
43. Fibonacci series
44. How to get the data from more than 3 table without use join ?
45. How does PHP work? 
46. What are the common uses of PHP?
47. What is the use of "echo" in php?
48. How to include a file to a php page?
49. Differnce between two dates
50. Php error handling questions
51. Difference between CURL and ajax 
52. Group by VS order by main Difference ?
53. What is pear?
54. What's the difference between an interface and an abstract class?
55. Differences of abstract and interface?
56. abstract class?
57. How to fetch last two records from the table
58.  i could do OOP
59. Phalcon framework 
60. Transform an integer to a string using only arithmetic operations. Known in C as 'itoa'.
61. accessing a class via :: means
62. do u know anything about php
63. Traits in php
64. who is the father of php?
65. They ask me to write an API to retrieve messages, retrieve a single message and to update a message.
66. Difference between GET and POST?
67. How to call Curl
68. Did you worked on payment gateway ?
69. PHP Array and Mysql Engines?
70. What is the difference between an abstract class and an Interface ?
71. sql statements
72. Did you use any frameworks in the development process ?
73. Given a sum and an array, print out pair of elements that contribute to that sum?
74. What does SOLID mean in programming terms
75. Responsive design
76. What is I in mysqli?
77. Do you have any experience with PHP frameworks?
78. I was given a task on machine to design/create a data base in MySQL for around 7 categories, and the key was to do task with PHP OOP's concept. 
79. Multithreading questions
80. Caching
81. Send a mail with attachment using phpmailer
82. Calculate the salary of all employees and print them basic, HRA, allowance, tax and education cress in pay-slip.
83. Calculate the education cress of all employees in the company and print them
84.  Display the 2nd highest net salary (salary after all deductions) among all employees
85. Rank the employees from highest to lowest. Please add a rank field in display grid. If 2 employees are drawing the same salary, their rank will be same. Following are the employees and their salary details: 1) Rajiv -- Basic - Rs. 5500 -- HR - Rs. 2500 -- Allowance - Rs. 1000 2) Meghan -- Basic - Rs. 5500 -- HR - Rs. 2500 -- Allowance - Rs. 1000 3) John -- Basic - Rs. 15500 -- HR - Rs. 7500 -- Allowance - Rs. 4000 4) Brian -- Basic - Rs. 10500 -- HR - Rs. 5500 -- Allowance - Rs. 3000 5) Rajiv -- Basic - Rs. 35500 -- HR - Rs. 13500 -- Allowance - Rs. 10000 Create the code in MVC model. Keep the model, view and controller layers separate.
86. Was asked to make a small Laravel project that backups all the databases(yes there can be multiple) on a click
87. What are the new trends in PHP
88. There are 8 stones, each has the same weight, except of one, which is heaviest. How would you discover which one?
89. Difference between new and old versions of PHP
90. New functionality in Laravel
91. My practical PHP achievements
92. My Projects, Challenges
93. My R & D track record
94. How will you load the model in codeigniter?
95. sessions
96. algorithm to find bishop movement in chess
97. Git, frameworks, linux
98. asked about dissertation for my masters degree
99. what additional value you will bring us to the company?
100. What is OOP and what are its advantages ?
101. How many years do you have experience with PHP?
102. how long do you want to work for ATL foundation if you get selected.
103. can you work under pressure
104. What do you know about DHCP?
105. Ask basic questions like OOp concept Php basic Sql Query
106. There is a programming exercise that you will code a car parking management.
107. http://www.geekinterview.com/question_details/83626
108. what is php,ajax,javascript,jquery,html?
109. Tell me about your self?
110.  What is MVC architecture?
111.  Type of Framework?
112.  Latest version for PHP and Bootstrap? 
113. Q.What are you Qualification?
114. When did you graduate?
115. Name at least 3 different PHP frameworks, and pros and cons of each one.
116. If I emailed you to offer you this position how quickly could you respond to me?
117. Tell us how you handled a very challenging technical problem
118. What is class and objects? And all about mysql and php?
119. How do you teach yourself new things?
120. how to set csrf token in codeigniter?
121. Create one simple admin panel. Where admin can add/update/delete product details like name, quantity, price, active. (Done) - Now the user can add product into cart after login (cart will be local, no need to save into DB) - When user checkout all cart related details are added into database. - Now the admin can see all the order details. - Admin can see the top 10 selling products. Other Info ------------------------------ - Use Laravel 7+. - Add proper comments into code. - Add 100k products using seeders. - Try to optimize DB query and relations.
122. Why do you want join this company?
123. Do you have experience with FileMaker?
124. Can you build a dashboard with a PHP backend?
125. Show how to traverse a tree.
126. What is my previous experience
127.  design patterns
128. object oriented programming
129. What is PSR-2?
130. question about mysql joins, etc
131. How does SSL work? 
132. Why do we need 3rd party SSL providers while we are able to create our own certificate?
133. PHP Frameworks
134. create a project with CRUD, one algorithm logic and insert data in db for testing.
135. Query to get the 31st highest salary.
136. What is usermeta function in Wordpress
137. Are you willing to sign a bond ?
138. I was asked to submit a practical project/test in PHP Laravel framework
139. What does "final" mean in a PHP class?
140. Technical questions related to PHP concepts like namespace, MVC architecture, sql, API integrations
141. wap to give output 00000011111 input is 01001011
142. Form validation using jquery .
143. System Test: Add, Edit, Delete, View user in PHP
144. Agile concepts 
145. how you would create a user login system from scratch (PHP/ Mysql)?
146. Difference between == and === ?
147. what's the purpose of vendor folder
148. What is SQl Injection?
149. How SQL injection can be prevented?
150. What is DOM?
151. What is cross site scripting and how it can be prevented?
152. What is Restful Webservice?
153. How delete operation can be performed using Restful webservice?
154. What is ajax?
155.  At last he asked me to write a program for all the number from 1 to 100 ,all the number that are divisble by 3 print 'FIZZ' ,all those number divisible by 5 print 'BUZZ' for thoose number divisible by both 3 and 5 print 'FIZZBUZZ' for other print the number itself (just find the mod and use if loop)
156. What do you think you can bring to CV-Library?
157. Bubble Sort PHP program by example, to find 2nd maximum number of the given array
158. SOLID principle, xss attack, cross site scripting prevention, REST vs SOAP, GET, POST, PUT, and other bookish definitions
159. They asked to rate yourself in the technology
160. Some questions about Coding standards like OOP, design pattern, clean code,etc.
161. What is difference between method overloading and overriding
162. Is login works when cookies disabled on browser ?
163. What happens when you use visit a website
164. What is POO
165. Do you work in NoSql also?
166. Second highest salary. * ** *** **** program
167. What programming languages do you know
168. What do relations in DB do and how do you use them?
169. opps question polymorphism, object access mode
170. What is the difference between unit and functional tests
171. What different in work beetwen Apache and Nginx
172. sorting of array in ascending order
173. Sort a array of objects based on one of the properties of the array.
174. Why did you use a custom API solution instead of an Open Source one?
175. How do you protect from a XSRF attack?
176. First she asked me asic concepts of php then she asked about mysql join queries.
177. What is MVC Framework, What are the most prominent features of CodeIgniter? Explain controller in CodeIgniter.
178. Who founded php
179. How to add aws plugin in PHP?
180. Sample streamed data Please write a program stream-sampler that receives and processes an input stream consisting of single characters.
181. SQL: you have a table with customers, with gender m and f. Write a query to update m with f, f with m in a single query, without temporary tables
182. how can you display 3rd highest salary from database? 
183. how can you handle errors in php? 
184. how to send a http request in php? 
185. In depth concepts of OOPS.
186. 1. Group by VS order by main Difference ?
187. print 1 to 100 no divide by 3 and 5.
188. Debugging the PhP codes.
189. How would you implement PHP/MySQL pagination?
190. What is the full form of PHP
191.  They also asked about web services and major focus of interview is MVC and CAKE PHP
192. What is session and cookies.
193. have you work wth mvc like laravel, ci, zend , cake & yii ?
194. Mysql join and grouping
195. inheritance, classes etc.
196. Technology related questions on PHP, WordPress, Shopify, Magento
197. What do you know about PHP artisan? Mention some artisan command.
198. Can you work independntly
199. How can we access the data sent through the URL with the GET method?
200. Tell me about your roll in the current company.
201. constraints and triggers
202. How will you develop database
203. What are SQL Injections, how do you prevent them and what are the best practices?
204. var_dump(0123 == 123); var_dump('0123' == 123); var_dump('0123' === 123);
205. What is the need of interface?
206. What are the best method for optimizing php or mysql code
207. How to reduce http request on page loading?
208. What is SOLID principles?
209. What is my experience with Laravel?
210. I was given to create a small module using Any framework or core PHP.
211. Praktische Erfahrung mit Symfony, REST, Docker ?
212. Part 1. They asked about basics of object oriented programing. what is inheritance, give me an example of a sql command Part 2. They sent a php file with about 400 lines of code and wanted me to implement a design pattern to that code. You have 2 hrs to complete the task.
213. 8 balls puzzle to solve
214. improve the code from the talent test according to modern software development practices. include unit tests
215. HTTP methods in PHP
216. php array functions,string functions ,laravel questions
217. 2. How can a Cookie Value be retrieved?
218. 3. Name the types of loops existing in PHP.
219. core php,js
220. Describe the request lifecycle in Laravel?
221. Write a recursive function that reverses a string
222. [1,6,5,4,2] -> write an algorithm to return second larger number in the array, in this case number 5
223. class Test{ protected $var; public function __construct(){ $this->var=1; } public static someFunction(){ return $this->var *= 5; } } What is wrong with the code ?
224. if(!(strpos($haystack,$needle)){ } What is wrong with the code ?
225. PHP and mysql questions as in other companies, OOPS concept, MySQL db concept like joins, group by, having
226. Write a PHP function to list out files on the html page that correspond to the filenames and extensions present in a directory, which of course relates directly to the type of work iDrive does, working with files, backups, and interacting with them
227. Write array element count without using count variable.
228. Difference between mysiam and innodb storage engine
229. maximum size of post request in php
230. maximum size of get request in php
231. maximum cookies which can be stored in browser
232. $x = true and false; var_dump($x);
233. $text = 'John '; $text[10] = 'Doe';
234. why to use hooks in ci
235. 13 : how to find datatype of $i ?
246. Make an app for Event Exhibition, which different events, and each event has stands, provide feauture to book stand with details and documents, show details of booked stands, email visitors etc
247. Design an app that handles a parking lot, and has 3 sizes of parking slots.
248. (Reverse a string, Ascending sort an array
249. Binary Search
250.  Will tell you to optimize your code and handle different test cases
251. types of mysql engines?
252. How to create object of Interface
253. How can protect my site from world class hackers ?
254. fibonacci, factorial, max, sort etc.
255.  triggers and types
256.  basic joomla questions
257. PHP basic questions, OOPS, Server configuration, MySQL Index, Joins, Optimization. MVC, JQuery... Zend Framework
258. How to declare an array in php?
259. It was about Symfony framework, multiple questions.
260. oops concept and basic of ci
261. 0128 vs 128, are they the same?
262. Do you have any experience with Database Architecture?
263. How to achieve multiple DB Hosts in PHP Laravel application?
264. What is autoloading classes in php?
265. 1. Simple questions like differences on implode, explode, required, include, and string functions
266. mysql self join
267. Variable name of max execution time constant in php?
268. Explain different types of arrays in php
269.  laravel and crud opration
270.  what is HTML DOM?
271.  What is inheritance
272.  array functions
273.  How to extract and store, Referrer link from the Contact us form of any wordpress landing page using PHP?
274.  Find a pair with matching sum equal to matching number
275.  Write a PHP programme to print all 0 to 1000 numbers which are even and odd.
276.  Are you familiar with agile practices?
277.  What do you understand by Eloquent ORM?
278.  Sql
279.  How would you uppercase a string, if you didn't have access to a stringToUpper method?
280.  Sessions and cookies
281.  Intermediate PHP and MYSql Questions, Project design and details.
282.  how to reverse the position of words in the string.->use explode() or split()
283.  Some basic OOPs concepts
284.  Find the last entry of the table
285.  All types of joins
286.  Write code to insert data in database
287. Find the count of status(even,odd) for even status.
288.  Write code to design a HTML page of any shape he provides. I was given 5 boxes to be fixed in entire page.
289.  How to create an array of a group of items inside an HTML form ?
290.  What are the encryption techniques in PHP
291.  A ladder of 10 feet is hanging from the side of a boat. 2 feet of the ladder is underwater. If a tide of 5m height comes, how much of the ladder will be submerged?
292.  PHP desiging patterns, best way to right program for Fibonacci serise.
293.  Laravel 5 concepts, PHP design concepts
294.   Describe the architecture of one of your projects?
295.   What are your future plans? How soon can you learn new technology upto working level?
296.   what is default port number of MySQL?
297.  what is the default SSL port?
298. what are joins explain briefly?
299.  what is the difference between inner join and left and right joins?
300.   There is an array with some elements and find out second max element of an array without using any built in function?
301.   Write a PHP for-loop showing odd numbers from 0 - 100.
302.   He asked me to create 2 PHP classes
303.   Plain sql question
304.   Describe DDD
305.   HR: Do you know link development? Why do you want to move to Link development? Tell me more about your self and old company? Why do you want to leave your current company? What do you expect from Link dev? Expected salary? When you are ready to move to link dev? Whats the obstacles do you face with your team? Tecnical: Do you know OOP? Difference between calss and abstract class What is the interface? Why should i use interface? Do you know Unit testng? Did you used unit testing before? Whats dependency injection And some exercise
306.  What is the "t()" function in your code?
307.  OOP in PHP: - Inheritance - Interface - Abstraction - Magic Methods
308.  How many years of work commitment we expect from you!
309.  Code for finding two numbers in an array in which the sum of them will be equal to some static variable value which was already defined.
310.  Ways to print an array
311.  Based on tcs ninja
312.  What is MVC, PHP , SQL
313.  How to create a session? How to set a value in session ? How to Remove data from a session?
314.  What is recursion? WAP for Fibonacci.
315.  $sql = "SELECT * FROM table as a WHERE a.id ={ $id }"; What is wrong with the code ?
316.  Have you ever handle one million user inputs in a second ?. Write down syntax for ajax call ? 
317.  Find the second largest of a table value?
318.  Find a string character count without using string functions ?
319.  Relationship between Inheritance & Access Modifiers
320.  What is Multiple Inheritance? 
321.  What is indexing in DBMS?
322.  How many engines are available in SQL?
323.  Run time and compile time polymorphism
324.  What are indexes ?
325.  What is Constructor & Ho w We Implement It
326.  6 Remove Duplicates rows from table
327.  var_dump('0123' === 123);
328.  Qual as vantagens do clean code?
329.  what is the view composer?
330.  Could you create a web application as a test exam?
331.  difference between innodb and mysiam
332.  string reverce without using php functions
333.  Ben je bekend met SOLID en DRY?
334.  class Helper{ public function getFormattedUser($a){ $user = new User($a); return $user->name.' '.$user->surname; } } Where is the problem on this code?
335.  Reverse of String
336.  Tell me some other software patterns, apart of MVC
337.  Which tool do you use to manage external dependencies?
338.  Do you use namespaces?
339.  What framework you use/ how many SQL experience do you have? How long you use it ? How many experience do you have on that?
340.  What does SOLID stand for?
341.  "Have you ever handle one million user inputs in a second ?. Write down syntax for ajax call ? Find the second largest of a table value? find a string character count without using string functions ?"
342.  What is XSLT?
343.  Which was your biggest failure?
344.  All the questions are related to PHP, Bootstrap, and Database. Ex: types of loops in PHP? What is the difference in col-sm and c0-md in Bootstrap and why we use this?
345.  Q2: What logic will you follow while creating simple Login form?
346.  What is PHP session?
347.  How To submit data of one page to another Page Without using GET and POST?
348.  What are the websites you've built in your previous years?
349.  There is no difficult questions just core php and system test about add, edit and delete.
350.  1.Object-oriented concepts. 2.Mysql Joins and Normalization and constraints. 3.Jquery basic questions. 4.Machin test to create API in Codeigniter.
351.  Do you have exprience in laravel, megento or wordpress.
352.  find minimum and maximum from 1 million numbers
353.  There is array of 1 million integers (numbers can be repeatative). find smallest and largest number.
354.  How to build a multi-user application in Laravel.
355.  How to get last date of month of given date?
356.  write a program add array value with function and without function.
357.  Solve the rubiks cube...how long will it take for you?
358.  What is Sql injection?
359.  Ask general question on php regading function nad string
360.  Give five array functions name in php
361.  How do you define a helper in Laravel?
362.  How can we get data between two dates using Query in Laravel?
363.  Tell me about Collection Framework.
364.  Q: How to delete a specific element in an array?
365.  Write a php program in a textbox. You need to make the program success with getting no warning and displaying the right output within the given timeframe.
366.  what are the successful thing in your career?
367.  Given a link to online app. How can you split this app for microservices
368.  Basic Questio of php and oops, array, array,variables that all.
369.  Some logic where user selects from a drop down, so that it should display records which is related to 4 tables. Submit through ajax & display the result.
370.  If I client wanted an app in addition to their website what would you tell them?
371.  Mysql Joins?
372.  Create a Fizzbuzz
373.  Name 3 of the 5 principles of object oriented development.
374.  Besides the question about interfaces vs classes, perhaps the most exposing question to me was, "Do you consider yourself more of a procedural developer, or object oriented?" In today's fast-moving technology skill set where advanced techniques and frameworks are touted, to admit I have been primarily procedural was a bit humbling; however, I understand I was in the #1 running for the position until they finally decided to simply not fill the position. Needless to say, of course, I did not get the job.
375.  What is Laravel and what is dependency manager in Laravel?
376.  What is Php ini?
377.  write a program to print palindrome from specified range
378.  Find the square numbers in the given range (x,y).
379.  Q. Write a console PHP code using Standard Input / Output for the following problem: Given N numbers, [N&lt;=10^5] we need to count the total pairs of numbers that have a difference of K. [K&gt;0 and K&lt;1e9]. Input Format: 1st line contains N & K (integers). 2nd line contains N numbers of the set. All the N numbers are assured to be distinct. Output Format: One integer saying the no of pairs of numbers that have a diff K. Sample Input #00: 5 2 1 5 3 4 2 Sample Output #00: 3 Sample Input #01: 10 1 363374326 364147530 61825163 1073065718 1281246024 1399469912 428047635 491595254 879792181 1069262793 Sample Output #01: 0
380.  What are different types of errors in PHP
381.  Three light switches in one room, three lightbulbs in another, you can only have on light switch on when you walk into the room with lightbulbs, how can you tell which light switch corresponds to what lightbulb? (Hint: The lightbulbs are incandescent)
382.  The coding challenge asked me to calculate students percentile rank using a group of data. It required me to provide testing, scalability, reusability, etc. with PHP.
383.  How would I optimize a db query
384.  Are Multiple inheritances supported in PHP?
385.  Your biggest failure and what you did after it happened.
386.  All the core concepts in PHP
387.  You tried your 100% to solve an issue but you didn't get succeed and your TL is not available/busy at that time. Then, what will you do?
388.  preg_split()
389.  Programming Component: How do you tell if a string is a palindrome
390.  Do you know SOLID principles?
391.  How do you extend two classes in PHP?
392.  how to solve the problem when the situation that over 100000 people use the system at the same time
393.  Which is best website according to you?
394.  What are OOP concepts ?
395.  Core PHP and OOPs Questions OOPs Programs Mysql Queries and Optimization concepts Zend Framework Questions Teams and Leadership Questions
396.  If I was familiar with ERP and Magento
397.  Create a CRUD API, and interface for it, add it to Github, create test cases
398.  They had me design a database and during the design they continually changed how they wanted the data to act or be stored while disallowing changes to the schema.
399.  Array Functions in PHP. Exception Handling.
400.  1) They have asked some questions in object oriented programming. 2) They have asked to write oops technique like inheritance, Polymorphism in php language. 3) They have asked about final year project .
401.  They asked to do PHP code for creating database and CRUD operation. And SQL queries like joins.
402.  1.Third parameter of explode 2.Question based on group by query 3. PHP logical questions
403.  Api Integration on machine
404.  what is default session time
405.  How familiar are you with different php frameworks?
406.  They asked me to import a 30 million row CSV file in MySQL. And show a view, with charts and filters.
407.  Are you comfortable working in more than one language?
408.  He asked about sql connectivity in php
409.  How to register a middleware in laravel
410.  Given an array of words, how can you reduce the lookup of all words that contain a given set of characters in O(1) instead of O(n).
411.  Draw for us how an ATM machine works.
412.  How do I handle situations where there is a conflict?
413.  Do you apply principles, patterns and proposals to your code, which one do you use?
414.  I have a bucket of 5 litres and a bucket of 4 litres of water. How can I make 4 litres? and then generic OOP questions
415.  They asked me how to create API ?
416.  Describe how Laravel containers are used
417.  Why do you prefer to use linux ?
418.  Tell us your experience in PHP
419.  Diff between datatype and datastructures
420.  SQL Queries , array functions, MVC Pattern, SQL transaction, Rollback
421.  1. Why do you want to leave your previous job? 2. Why is Java Platform Independent? 3. What do you know about Quick Sort? 4. A pattern question, program to draw a specific pattern.
422.  8: find names of students whose age is greater than 21?
423.  Programming Component: How do you prevent XSS/SQL injection on a simple example
424.  How should you go about finding a bottleneck at some page at your site? (e.g. one taking too long to load). Then, if it's the database, how to solve that.
425.  var_dump('0123' == 123);
426.  $array = array( "1" => "a", "1" => "b", "1.5" => "c", true => "d", ); print_r($array);
427.  var_dump(0123 == 123);
428.  An SQL to display the count of duplicate entries.
429.  What is magic function in php
430.  Recursive function
431.  To code a basic form using HTML, PHP and database
432.  Just asked to write a program to display the table data
433.  Why CI not Joomla ? It was really difficult to explain.
434.  Q) take input a number N. if N is even display some error else display a matrix N*N all border elements and both diagonals elements are * and remaining elements as _ .
435.  What would be another efficient way to divide a integer by 2 ?
436.  How would you write a palindrome function?
437.  what is recursive functions?
438.  Explain preg_Match and preg_replace
439.  What is Interface ? What is Abstract class ? Difference between them ? Database design of online shopping cart. Different questions on design and various modifications. Types of error in PHP ? How to optimize websites ? How to swap 2 number w/o 3rd variable ? Mysql Engines Mysql Index. Disadvantages of it. Various queries (finding duplicate entry, finding 2nd highest entry, etc) Finding 5th child in jQuery
440.  Have you contributed to open source?
441.  Then I asked cakephp Questions.
442.  They mainly focused you are able to work with JSON data and AJAX
443.  write a code for database connection
444.  Program to validate emai id using javascript Define multidimensional array
445.  associate array
446.  update and insert in sql
447.  What are the different types of JOINS ?
448.  About API Integration, Working with security
449.  array merge and array combine
450.  What is Inner Join?
451.  Write a php program to produce this : Input: we are hiring Output : ew era gnirih
452.  There are 3 light bulbs in a room. The switches are outside for each bulb. You are allowed to go inside the room only once. How do you determine the connections to the bulb and switches?
453.  What are a few personal web projects you've got going on?
454.  To write a php code to print star pattern.
455.  Life Cycle of laravel, Why are migrations important?
456.  Eloquent Query Question, 1) One To One 2) One To Many 3) Many To Many
457.  What are datatypes in mysql?
458.  How to destroy sessions?
459.  what are access specifiers?
460.   Can you write me a PHP form with validation?
461.   SQL Injection, XSS Attack, etc.
462.   2) Write a program to print prime number between 499 and 699
463.   what is file handling in PHP and which functions used?
464.   How is php and mysql connect?
465.   Q. Use of "final" keyword.
466.   They gave me an array starting with 0's then 1's need to find the first index of the number 1
467.   what is POD
468.   groupby query and joins
469.   What is array function,string funcction,basic php questions, Laravel default structure,
470.   How to make Laravel package?
471.   hastable
472.   Which difference between Constructor and Abstract Сlass and why?
473.   How many database indexes can you have in a single table?
474.   Difference between sort by and order by.
475.   how would you go around solving the N + 1 select problem?
476.   anagram
477.   What is Middleware in Laravel?
478.   what is index in mysql
479.   What is faster $i++; or ++$i;
480.   distribute system design
481.   Database design was challenging.
482.   database schema design
483.   Where do you see yourself in N years?
484.   Laravel middleware, Eloquent, migrations, seeder, artisan , MySQL joins
485.   Explain what the composition is?
486.   OOP, OOD, ACID, DB indexes, PHP traits, micro-services, docker, testing, TDD, DDD, Architectural patterns, NO SQL, SQL Joins, group by
487.   Describe one of the anti-pattern in OOP
488.   What other design patterns except for SOLID do you know
489.   What is a service container and how it works
490.   1. Basic PHP knowledge. Types, Arrays? and etc 2. Writing MySQL query (3 different query). 3. OOP questions 4. Js questions (types, closure, execution context) 6. Css questions 7. HTTP methods, Status codes 8. Dessign patterns only about singleton
491.   questions about SQL joins and different type of joins. in a left join, what will be returned from right table if don't find any matching rows from the right table?
492.   sort a array of objects based on one of the properties of the array.
493.   Basic PHP, SQL, Object Oriented programming questions. Like what is expansion for PHP. What is abstract class. What is a class and what is a object. Difference between PHP Version 3,4 and 5. Singleton?Different Joins in SQL.
494.   Can you name most of the common HTTP status codes?
495.   How do you scope vars in PHP?
496.   Have you worked with MVC?
497.   Tell me about MVC in PHP
498.   1) Difference between array combine and array merge 2) Preg_replace 3) PEAR in php 4) REST VS AJAX 5) REST VS SOAP 6) Second highest salary 7) sort a array with predefined function 8) Create a class and call add and subtract function 9) Mime type 10) Markup language used in rest web API 11) why this error occur header already sent. 12) difference between put and post 13) HTTP method supported by REST 14) Mysam VS Inno Db 15) INNER JOIN VS LEFT JOIN 16) TRAITS 17) FINAL CLASS 18) MAGIC METHOD 19) complex mysql query 20) PUT VS POST 2nd Round 1) how to implement Security in app 2) MYSQL DB question what is layers in mysql , myisam VS innodb , master slave, optomise datbase , datalayers 3) Server commands TOP , one , c
499.   What is Stack, Linked List & Queue?
500.   Write pyramid structure without using PHP function ?
501.   Are objects passed by value or by reference?
502.   How do you call the constructor of a parent class from a child class?
503.   What is meant by urlencode and urldecode?
504.   How do you get the headers of a request?
505.   What is multi-tenancy?
506.   What is searialization
507.   what is use of traits
508.   singleton Class
509.   use of Trait by Creating Singleton Class
510.   best PHP framework to develop ecommerce website?
511.   How do you work under pressure?
512.   How / why would you use a composite key (in MySQL)?
513.   What is PHP, Define Client side validation and server side validation. Define GET, POST, PUT METHODS. Define Ajax., Smarty, framework. Most Important OOPS concepts.
514.   How do you setup CI pipeline ?
515.   What are joins?
516.   What you know about micro-services and why we need it? (answer as much you know)
517.   1 What's the difference between __sleep and __wakeup? 2 what is the definition of a session? 3 What does $GLOBALS mean?
518.   explain what is die() function
519.   Find min and max from array of 1 million
520.   Data abstraction vs polymorphism
521.   Do you have experience working with rabbitmq?
522.   Variable name of max execution time constant in php?
523.   WordPress i18n Translations - Where yoiu will have to translate string with php variables using .mo files.
524.   what are the version of web browser
525.   What is this and super keyword? What is an Interface? Factorial using recurssion Inner join and left outer join Number pattern
526.   As per experience Like about Rest API's ,auth, code security,3rd party integrations
527.   What is REST API (never entertained a discussion on it or asked me how do I design a set of endpoints).
528.   The value of the variable input is a string 1,2,3,4,5,6,7. How would you get the sum of the integers contained inside input?
529.   Q: What is inheritance in java,singleton class,Exception handling,and a lot of sql query they will give you table and ask relevant sql query based on the table.
530.   JWT
531.   Api security
532.   Q: Difference between $var and $$var?
533.   How do you create a new branch with git?
534.   Have you ever used an SVN for source control? Which ones?
535.   Questions about multithreads and some java basic questions.
536.   What is AJAX?
537.   About HTTP and Database Queries
538.   What does var_dump() function does in PHP?
539.   Difference between REST and Web Service there Types, Web Scrapping , AWS Services,Machine Test
540.   All basic question related to Laravel & PHP. session cookies routing middleware etc
541.   What is 2 tier and 3 tier architecture?
542.   Why should we use RDBMS or whaat was challanges with traditional file systems?
543.   what is advantage & disadvantage of MongoDB?
544.   Sql joins and types, sql engines, jquery basics, php oops
545.   Use of CORS in api development
546.   Create a web page of Pizza Delivery order and calculate the total of order and display
547.   Do you like working on legacy code?
548.   $str1 = 'yaboalkdfjal'; $str2 = 'yado'; if(strpos($str1,$str2)){ echo """ . $str1 . '"does contain' . $str2; }else{ echo """ . $str1 . '"does not contain' . $str2; }
549.   What are abstract class?
550.   Write a simple program to handle a file uploads on a given form.
551.   Aptitude-You have 2 phones. You are on a 100 floor building. You drop the phone from a particular floor. It breaks or survives. If it survives you can throw the same phone from a higher floor. How many attempts do you need to identify the max floor at which the phone doesn't break when thrown down?
552.   What are the main differences between const vs define ?
553.   Implement a Priority Queue in PHP
554.   Method overloading ,method overriding,JavaScript basics,java,SQL queries especially and about project.
555.   Jobs and queue in Laravel
556.   Psr standard
557.   Hooks in codeigniter, precontrollers and postcontroller
558.   How do you keep up to date with latest technologies and trends?
559.   difference between string with single quote and double quote in php. "string" vs 'string'
560.   Design a vending machine
561.   What is PDO in PHP? What is the use of ini_set()?
562.   what are Constraints in mysql
563.   what types of selectors in PHP?
564.   Types of join, inheritance supported by php, Access specifiers, triggers, database queries.
565.   What is web clustering?
566.   difference between primary key and unique key ? Difference between index and primary key
567.   Do you know PHP and FuelPHP
568.   relocate,salary,reading for api, reading from csv and merge data
569.   What could be a downside to Laravel eloquent
570.   What is unit testing, integration testing, specification testing
571.   MySQL related questions and queries, joins, sql functions, triggers. How to copy data of one table in another with a query?
572.   If we want you to give yourself a grade from 0 to 10 about PHP language and Laravel Framework, what would be the grades?
573.   Difference among various php versions
574.   Describe how a refresh token works?
575.   insert update delete in PHP
576.   Print Pattern, Databse optimisation, php string funtion
577.   Recursive function in mysql
578.   difference between die() and exit() function
579.   associative array
580.   Find number of lines, chars, words in a file.
581.   CRUD Operation in codeigniter. Product table and category table. Add product edit product delete product etc
582.   Relationships in Laravel 
583.   Which method is used to start the session?
584.   What is ascii?
585.   Do you know what PCI is?
586.   What is reflection
587.   What is normalisation What is polymorphism Sql Querys
588.   How to scrape the data from website using CURL?
589.   How can i execute PHP File using Command Line?
590.   What are different type of sorting functions in PHP?
591.   Find the defect in the SQL query and correct it so that the query executes : SELECT ID, YEAR(billing_date) AS billing_year FROM table WHERE billing_year <= 2015
592.   what is inheritance? How many types?
593.   What are ternary operators?
594.   Expect behavioral and code structure / paradigm questions.
595.   Lifecycle of code. From request to response.
596.   Differences between JWT and OAuth tokens.
597.   What is hooks in ci? What is traits in ci?
598.   Please describe yourself using JSON.
599.   are you aware about mongodb?
600.   trigger & stored procedure
601.   function overloading
602.   Type casting & type juggling
603.   What is the last version of PHP
604.    Differentiate between delete() and softDeletes() 2. Define Laravel guard 3. what is facade
605.    Difference between unset and unlink?
606.    A Cipher text paragraph was given and the Standard distribution of letters in the Decrypted text was also given.Based on this we have to decrypt the text..
607.    strstr() use in PHP?
608.    The homework was to write a Drupal 7 module that displayed a list of posts updated on the current day inside a block. The module needed to have a test case included.
609.    What do you save for product information in cookie? How to retrieve cookie information? Get max salary without WHERE condition in SQL query.
610.    Is HTTP stateless or stateful
611.    wap to find max prime number from an array
612.    How can u calculate date difference in php What is dot operator Print array without loop
613.    What size teams are you used to working with?
614.    What is Cross Site Scripting in a nutshell?
615.    What are the differences between versions 5 and 7 of PHP?
616.    What are Events in Laravel?
617.    what are cloud computing advantages, what is Caching, Docker
618.    oops concept SQL queries CRUD operations set method why $ used
619.    How do you make a file executable in bash.
620.    5: Triggers ,Stored Procedures, Events
621.    7 : Self join query
622.    How to validate the password field with regex
623.    abstract classes
624.    What is ajax attributes ?
625.    What is the difference between using PHP and the Zend framework?
626.    find second max number from araay
627.    How does MySQL create indexes
628.    Did ever work with SPL functions
629.    Create a middleware to authenticate against JWT in Laravel.
630.    How to migrate a monolith project to microservices.
631.    How much work have you done with database design or maintenance?
632.    What's the best way to approach the open-closed principle using Symfony pre-built feature
633.    Concurrent Access and Locking - how to handle it and what's the default state of MySQL database
634.    I had to refactor a sample of code based on SOLID principles. On trial day I had a feature from backlog to refactore and propose a new architecture.
635.    how does db indexing work
636.    What is CSRF, what is sql injection, what is cross site scripting?
637.    What would you like to see on your tombstone?
638.    Do you know how SQL escape works? explain how it is works.
639.    How do you protect from a SQL injection attack?
640.    Interview questions will be easy: 1. Joins in mysql table. 2. Design a dynamic webpage whether its a login form or anything. 3. count() funtion mysql etc.
641.    describe slim framework?
642.    What is a web server?
643.    What types of APIs? (answer with details)
644.    How to write a clean code? (answer with details)
645.    what is the difference between cookies and sessions system test- crud operations
646.    Difference between constructor or distructor in php?
647.    How can we convert the time zones using PHP?
648.    Write syntax to create cookies? JOIN queries syntax ? Several real time problems
649.    What is database engine role in Database, why they exist ?
650.    What is abstraction.and What is the difference between abstraction and interface
651.    Middleware
652.    Questions related to recursion and join.
653.    - Simple encapsulation, polymorphism - Some basics of the Framework - MVC, PHP, MySQL, Design integration - Some technical questions and use case based
654.    what msqli_connect() function return answer is connection
655.    what is implode explode
656.    Polymorphism, PHP magic methods, reverse a string without string concatenation, swap two integers without using a temporary variable (they give you hints, if you need), why use private and protected key words
657.    In PHP what is the difference between a Class and an Interface?
658.    PHP and MySQL syntax 1. DML Statements 2. DDL Statements 3. DBMS/RDBMS 4. Subquery with example 5. Core PHP questions
659.    What is oracle's latest version?
660.    Difference between ksort() and usort() functions.
661.    what ob_start ?
662.    what is cURL , SOAP , File handling , have you used Session & Cookies , what is inter-relation b/w them ?
663.    Any experience with Laravel/PHP work?
664.    Q: What are the types of joining in the database are used?
665.    how mongodb is better than relational databases?
666.    Why you want to join Contorian.
667.    Practical Test: >> Three Questions were there 1. Draw a pattern. 2. Ajax request. 3. CRUD application. F2F interview: 1. What is indexing in MySQL. 2. What is the difference between abstract classes and interfaces. 3. sessions and cookies.
668.    Difference between HTTP and HTTPS
669.    1. write a program to find the number is prime or not.
670.    1. How to provide security to your website 2. what is crossscripting 3. Explain mysql and joins 4. what would be a change which you wish to make in society
671.    Talk about PHP opcode caching.
672.    Implementing a Priority Queue.
673.    1) Write a program to print nth position from fibonacci series.
674.    1 divisibility test
675.    Folder structure of Cakephp Relationships Validation MVC
676.    Q. Name of superglobals.
677.    Q. Name of SQL Engine.
678.    What features do you like in php7?
679.    what are different design patterns
680.    Pattern Programs
681.    PHP associative array add and delete operations
682.    Basic PHP questions , access modifiers, abstract classes, connecting to DB, where are they used? provide a good example?
683.    PHP Arrays, MySQL , Rest API etc
684.    REST API authentication
685.    What is header, tcp/ip, ajax, http, json, response type, post, joins left join etc
686.    htaccess file is used for?
687.    What is GDPR, Hipaa security rule, Security laws in India, Europe and US
688.    Print below pattern using PHP 2 2 4 2 4 6 2 4 6 8 2 4 6 8 10
689.    Dipendancy injection
690.    Difference between primary and unique key
691.     SQL Injection CSRF Token Hooks in CMS How to avoid sql injection attack PHP most used functions
692.     write MYSQL Query for selecting top 3 employees with maximum salaries
693.     Q: You have a DB which contains 10 lakh SMS, How will you define your architecture to send 10 Lakh SMS in 1 Day..?
694.     What is difference between an interface class and abstract class?
695.     what is an ORM
696.     MySQL joins
697.     1 what is PHP 2 : codeigniter in helper 3 : helper used then remove Helper 4 : what is array in array print to echo 5 : what is api 6 : what is third party api 7 : what is domain 8 : SQL full form
698.     Caching mechanisms - Redis, Memcached and their distributed nature.
699.     Perform a mock pull request review, identifying areas of concern or improvements in terms of performance, security, maintainability etc
700.     In 2nd and 3rd round they asked questions based on javascript and PHP 1. Use of const, var, let 2. What is callback function. difference between call back and promises. 3. What are hooks and how to use them. 4. Difference between class,library, helper. 5. List some basic helpers. 6. database setting questions 7. PHP mail function 8. What is API and what are uses. 9. What projects have worked on.
701.     DDD and micro-services, life cycle of a single HTTP request, SQL engines insides, some data modelling...
702.     How to scrape a website and find keyword density.
703.     About PHP MVC ZEND MYSQL
704.     PHP Login Register with database with session being carried on all pages.
705.     1. Codeigniter hooks 2. Laravel middleware 3. Templating engine 4. Docker 5. A same old internet picked logical question.
706.     Revert a linked list using recursion.
707.     triggers in MySQL, Web services tokens, authentication and authorization.
708.     Checked tech background and given homework to build a small API.
709.     Array, superglobals, Functions, Coding like array sorting.
710.     prototype and plugin development with jQuery or javascript
711.     Session, db queries, opps, array, string
712.     what is your favourite PHP extension :-)
713.     What sized websites have you worked on in the past?
714.     swapping dbms
715.     Differrence between mysql_connect and mysql_pconnect?
716.     What are magic methods?
717.     Write some string functions?
718.     What is the difference between restful API and SOAP?
719.     What is the life cycle process of Laravel?
720.     1. What is an artisan? 2. What is model? 3. What are the default route files in Laravel? 4. What are factories in Laravel?
721.     Online test, Oops , php 7 , javascript ,let , trait
722.     what is heredoc in php
723.     Write a closure.
724.     How do you balance a binary tree?
725.     How would you describe a trait in your own words?
726.     What is JSON? What are its common usages?
727.     When writing a class, what are the three scope levels available in PHP? Give a short description of each.
728.     PHP OOPS, PHP Array functions, MySQL index & Optimisation, Procedure, Trigger, PHP FIle handling (Read data from a file, Write data to a file), basic Linux commands, GIT commands
729.     Q: Make a full-pyramid pattern?
730.     cron job
731.     N+1 problem in laravel, session hijacking
732.     Difference Between $ and $$ and $$$ in PHP?
733.     How would you fix lack of multiple inheritance in PHP
734.     SOLID, Patterns (architectural and design), Testing, BDD, TDD, DDD, OAuth2
735.     Describe the variable visibility scopes in PHP.
736.     Questions on solid principle , optimise slow queries , process for epic stories in my project.
737.     Describe building blocks in Domain-Driven Design
738.     whats the angle between the minute pointer and hour pointer at 3:15
739.     I was given a logic question where you have 5 balls. One of the balls is heavier than the others. What's the fewest number of times you have to compare weights to figure out which ball is heavier.
740.     how to merge two tables in SQL?
741.     1) Tell me about yourself?? 2) write a note on a topic which is not related to technology??
742.     Tell me about static variables
743.     1. Display sum of 1 to N numbers 2. Display 1-100 numbers in each line where if it is divisible by 3 then '***' if by 5 then '***' 3. Write code to display a square with ' * '
744.     If you are in the race and you crossed the 2nd person in the race then what is your position?
745.     Estimate how many people get married in the United States every week.
746.     ACID
747.     There are 8 stones, each has the same weight, except of one, which is heaviest. How would you discover which one?
748.     1. what is call by reference in php? 2. difference between require and require_once 3. stack and queue, how this related to sorting function? 4. what's the difference between == and ===?
749.     Write a loop that takes POST data and creates dynamic variables on the fly.
750.     1.hr interview-they check your verbal and written communication ability 2.written test consists of 10 questions with mix of javascript and php 3.technical test - here they ask you to install LAMP ,Wordpress, Virtualization and/or FTP
751.     Q: Please tell me the message brokers you've worked with.
752.     What I know about Mphasis?
753.     Island problem and some behavioral questions.
754.     System design, class design for escalator
755.     Explain Interrupt handling with example
756.     Arrays Palindrome Sorting Searching Patterns
757.     Explain Dependency injection with an example
758.     Mutate a given input string
759.     How to scale model on cloud
760.     How to analyze the code
761.     what is dao in room db
762.     SQL based were asked, specially sub query
763.     How to override a hashcode function.
764.     Reverse a singly linked list
765.     Find min of average data.
766.     Questions for first two rounds. - Introduce about your self - strength and weakness - challenge faced and other general questions Questions 3rd round (technical) - Find the Errors for given snippet - question on bit shifting - arithmetic and assignment operators' execution preferences
767.     extension of kadane algo . circular array given
768.     What is the difference between DDL, DML, DCL?
769.     Something about a binary tree traversal
770.     How is your understanding about data communications and hardware? What is the difference between TCP and UDP?
771.     Q: What are the different API architectures and how are they different from each other?
772.      Spark Question
773.      Design pipelines
774.      General database system design questions.
775.      Basic technical questions related to coding and especially for SQL (PostgreSQL).
776.      Bubble sort, SQL query to find second largest salary
777.      What is IoC (Inversion of Control)?
778.      Optimize the code given code.
779.      Core Java, microservices, Scenario based questions, Jenkins, database related question, data structures. Script to create, write into a file.
780.      What things you don’t like at work? Dependency injection Difference between BigDecimal and double
781.      1: Code assignment, took around 3 hours 2: Technical interview with the tech team, took 2 hours around 3: 2: Technical interview with other tech team, took 2 hours around
782.      What is your favorite language? Why java is platform independent? Write code on the thing specified by interviewer Questions on DSA & projects done
783.      Write a code for Reversing a String.
784.      Design the System just like carousel
785.      sql quries on join condition , aggregate function , keys and constrains.
786.      Heap Map Graph Linked List Queue
787.      Explain the different use cases for different hooks.
788.      1-Star Pattern 2-OPPS question 3-we need to find the count of the pair in a array whose sum is equal to the target value 4- we need to print the count of the even word int the given string
789.      1) Immutablity of a class(Show an example in IDE) 2) How will you sort a salary of an Employee? (Show in IDE) 3) Once Sort Remove the 4th Highest Salary of an Employee? (Show in IDE) 4) What are Generics? 5) Are you aware about the Design Pattern? (if yes then explain ) 6)What is Multithreading, How you used that in your project? 7) What are Concurrent HashMap? 8) What are HashMap?
790.      Structs Vs classes, what experience I had with what architectures and so on
791.      The process is as follows here :---- 1) Online Test 2) Three Technical rounds(major focus was on java + OOPS+ multithreading) 3) DBMS+Cloud+ Basics of Computer fundamentals 4) Rounds were easy if you know DSA NOTE:- I was give positive feedback and at the end of HR round, they said we can't give you more CTC as there range in only 10-11Lakh. The worst part is HR's are very inactive and they don't let candidates know the whole process they kept in dark room. Rounds are very easy and interviewer don't have much knowledge about DSA so they ask repeated OOPS question to judge you and pass the time. Such pathetic experience I had with them. I never recommend anyone to go for interview with this company if you have any other job in hand. They initiated my rounds by saying we can give you this much but at the end they put me on hold that we don't have enough budget now. Very Bad and first time I have seen such services, they wasted my whole month and even not replying to mails even after many follow-ups. DONT GO WITH NAVIS.
792.      Clone a singly linked list using two pointers.
793.      - Write a SQL query to join 2 tables
794.      - Given two classes written in C#, you should write constructors for them. - If you have any edits to the classes to achieve polymorphism. - Problem Solving: You have an array (not sorted) and you need to print the repeated number. - What is meant by that REST Methods are idempotent? - To build a sign-in API, what HTTP method is more applicable? - The rest of the interview was behavioral questions.
795.      Interviews themselves were more conversational, but with one technical problem to solve. • Python functions: parameters, *args, **kwargs • Lists vs Arrays • Class vs instance variables • Reading files • Exceptions • Sets • OOP 1. Deep copy vs shallow copy 2. Object serialization 3. Microservices a. Scaling up performance b. Horizontal vs vertical scaling 4. Pythonic way of checking palindromes 5. Reading files a. What if the file has a billion+ lines? b. Multiple ways to do this 6. Behavioral a. Time when you've mentored someone b. Time when you've presented to a large group c. Talk about a relationship you've built at your work place d. Time when you had to convince someone something e. Time when you had to foster collaboration between multiple teams f. How do you do approach research? Time when you turned a problem into an opportunity
796.      What is agile methodology? What is exploratory testing?
797.      What’s are the pros and cons of a garbage collector?
798.      How would you fetch a http resource in a browser, how would you implement it yourself? What OS calls would be needed?
799.      What’s the difference between memory management in c/cpp and say rust?
800.      Oops, APIs, teamwork behavioral, how you learn new languages/tools
801.      This was asked multiple times: describe a conflict situation you handled as a manager and how you dealt with it?
802.      Given a list of users and a list of groups of users, how many SQL tables would you need to create a schema for that relationship?
803.      The first coding problem is Count Family logins, which can be solved by using hashmap and the second one is Shipment Imbalances. Both problems can be found in Leetcode.
804.      Please create a web app for an online notebook.
805.      Q: Discuss a time that you disagreed with a colleague, and what you did.
806.      when and why would you use core data?
807.      What is data transformation in SSIS?
808.      Approach to reverse an array
809.      What do you know about Freetrade?
810.      A cognitive test and some questions about promises, settimeout, and the output of the code on some scenarios.
811.      How would you manage version control?
812.      Oops concept, PHP basic + advance.
813.      Why string is immutable concrete hashmap design pattern spring annotations
814.      Design a ticketing system with a way to store logs submitted with tickets as well
815.      On SDLC and coding based questions on palindrome, prime numbers
816.      Solve leetcode medium and hard problems
817.      regex apply
818.      disadvantages of ORM, app-level improvements
819.      System design design a tagging system
820.      Code 1 and 2 Write a ratelimiter, and calculate the size of the files on a system, basically do a calculation on a list of a list, and sort a list
821.      1. Initially the assessment was to display posts and individual post with pagination in Vue, vuex and vue router. 2. Pair programming with the team on JS and CSS flexbox. 3. Manager round. 4. HR round
822.      Initially interviwer start with introducting my self. asking about projects. after shifted to technical part which will be asking like 1. Explain the worker process ? 2. What is mean by web api? 3.what is mean by action filters? 4.what is mean bu normallization? 5.write a program using array list find the all the values in array?
823.      Ingesting, transformation of data in cloud storage platforms like ADF
824.      What is indexing in mysql
825.      Basic opps concept, Detail project discussion, SQL queries, coding question.
826.      Spring Accutator SOLID principles Kafka duplicate messages
827.      Scenario Faced , failure in life
828.      Coding questions: 1. A hard leetcode question 2. Network/IP address validation question
829.      Two technical rounds followed by hr Rouns. Prepare core java concepts, spring, spring Boot, Hinernate, JPA , weservices like SOAP Rest and some Basics Programing Questions and caching concepts in hibernate
830.      Tell me about your self and then coding question
831.      Entity Framework, Cache and how to develop it in the program, Session and which session will use under specific conditions, How to create User Control, Page Load / Unload which will call first (Master page, content page, user control) New keyword ref in class The disadvantage of the Factory method webservice vs WCF SOA State Management Pagination on DB Level How to encrypt DB data, which library you have used Solid principle Design Patter How to implement Thread-safe Singleton Abstraction VS Virtual
832.      - Make a LWC that receive the recordID and display inside a lightning input form the sobject account as well display inside the lightning input form a LWC lightning input text that get the object name based on first result
833.      - Write a SOQL query that get user data based on the last user who view account object
834.      Design a system that keeps time synchronized across processes on remote machines using network messaging.
835.      What kind of data structure to use for a problem.
836.      Sample: if password is passed through a request body in https, is it protected
837.      Have you ever had a conflict with your team member. How did you resolve?
838.      Design and talk through a basic messaging architecture in response to requirements given by the interviewer.
839.      First part is multiples choices questions about http, thread , object and class(oop)
840.      STAR Questions, easy AWS questions
841.      If you have two deliverables that need to be met at one time, what will you do to complete both requests.
842.      design a sql query and with a minimum of t00
843.      fibonacci related question. window functions in postgres. database engine related questions. DB design question.
844.      Build a sudoku solver in 50 mins without using Google.
845.      Javascript basics like promises, callbacks, and async-await. React questions like class components, functional components, hooks
846.      What did you when you were aware you will not be able to meet the deadline?
847.      What is the difference between TCP and UDP?
848.      Self Introduction Are you Relocate You have any offer in your hand Call by reference and Call by value
849.      Basic OOP questions and some stack/queue based exercises
850.      Q1. Tell us about yourself. Q2. What are your strengths? Q3. What are your weaknesses? Q4. What is programming? Q5. What do you know about our company?
851.      I remember only some of my questions, very few. "Tell me about yourself" "What is primary key in SQL?" "Tell me about RDBMS"
852.      Select count(*) from table1, table2; here table1 has 25 rows and table2 has 50 rows.
853.      How many water balloons fit on a bus?
854.      Describe an interesting project you are working on.
855.      #1: Tell us a bit about yourself. #2: Why have you applied for this internship? #3: Why have you applied for an internship at our company? #4: Why do you want to work in this industry? #5: What are your strengths? #6: How do you prioritize your work?
856.      Binary Search, System Structures
857.      difference between put and patch, http status code, bundling, partial view, view body, adding default route
858.      Technical questions were focused on my resume: SQL, API, Object oriented concepts, Selenium exercise
859.      Implement a system to manage a parking lot. In a pseucode way. Think of the object oriented principles, and databases.
860.      What do You do when You receive a pull request from someone?
861.      What are the different types of EC2 instances based on their costs?
862.      1. Sort the array 2. Stair case problem - Dynamic Programming
863.      Stacks and Queues and the differences.
864.      Can you find the no of nodes in a Linked-List without traversing it?
865.      Solve a code problem about a maze and finding a path using Java or any other languages you are confident with
866.      Binary search tree types of stuff.
867.      Can you tell me some books about design patterns, not just teaching how to code stuff directly?
868.      Do you think you are a go-getter?
869.      - API design - Websockets , Message bus and pros / cons - PR reviews
870.      Had to build a basic full stack app within 4 hours.
871.      Why do you want to work at Prolucid? Standard Behavioral questions.. Where do you see yourself in 5 years?
872.      Multhreading, LC easy and medium problems, OOPs concept, design patterns
873.      Threads and garbage collector in depths
874.      1)reverse of array 2)What was your project ? 3)Preferred programming language
875.      What is retaining cycle, and how can one prevent it?
876.      What is the difference between unowned and weak?
877.      Dependency Injection, API verbs, Event Loops, WebApis. 2PC transaction
878.      who is your role model?
879.      Sorting question, string palindrome problem
880.      Write code for Reverse linked list.
881.      how about SDLC method and debugging
882.      Design the classes for an organism Prime numbers
883.      Explain the OOPs concept? Why multiple inheritance cant be achieved in java? Why overriding is not possible in constructor?
884.      eventloop, trigger, singleton pattern, memoization, authorization, authentication,lazy loading, Streams, Buffers, SPA, overloading vs overriding, generics, http methods, interceptor, middleware
885.      - Why Cambridge Intelligence? - Favourite programming languages? Why? - Design decisions related to your programming task - Lots of talk about past projects - what was it? what was learnt from it? what would you do differently? - Discussion around university courses - favourites? least favourites? tasks? teamwork?
886.      What's a binary search tree?
887.      Remove duplicate elements from array. Difference between overloading and overriding.
888.      What is the difference between Table and View in SQL?
889.      Experience with TDD
890.      MANUAL AND AUTOMATION Regression and retesting Bug life cycle
891.      How would you investigate a production system that is currently taking too long to process requests? Which monitoring tools would you use? Could you point the main differences between RabbitMQ and Kafka ?
892.      What is event loop and how does it work in setTimeOut
893.      Arrays Bst Hashmap Oops Multithreading
894.      BST- Merge two BST DP-Matrix Multiplication
895.      What is Sql indexer? Routing in MVC, http status codes
896.      BFS and inorder, preorder, postorder traversal
897.      NDA but basically, some DFS problems
898.      SOLID Principles CI/CD Pipelines Part work experience
899.      A very in depth question about Data Structures that no leet code prep could prepare you for. I believe the question was given that way to see how you think through problems
900.      Software engineering concepts and architecture
901.      How would you search for a specific email address in a list so that each key pressed reduced the list?
902.      What is a rest api
903.      Creating a CRUD (client manager) in a period of 2 hours
904.      The Lottery question - given a number N, write a class that allows a user to call getK and receive K different balls (with different numbers), chosen randomly from the relevant balls that are still in the system (not previously returned to customer). All numbers are unique, and should be from 1 to N.
905.      What are deadlocks What is polymorphism? Different types of polymorphism? In function overloading, how compiler knows which function to run? (Internal working) What are virtual functions. What is NAT? How https works? Asymmetric and symmetric encryption. Security devices at different layers of the network. What is arp poisioning? Most specific route in overlapping subnets. Design a load balancer in C++. How memset works Stack and heap in memory layout New and delete Malloc calloc and free Seperate linked list odd and even Templates in c++ Security at different layers of network VLAN ACL Agile Some behaviour questions
906.      array storage classes logical questions c programming questions
907.      Theory questions on golang. Coding problems related to go routines, channels. Basic networking questions. Rest api and gRpc.
908.      A short paper full of technical SQL questions
909.      how to install php? feature of html language.
910.      What is the latest version of laravel?
911.      A top K variation problem
912.      Linked lists, DS and A, etc
913.      Dependency injections Polymorphism Entity framework
914.      Database: sql unite, group by, SQL Common Table Expressions (CTE), inner join, outer join, and example of sql select find duplicates in a table.
915.      Experience and interest in writing high quality open source software.
916.      Build a MCQ website and send the screen recording of it.
917.      ACID property, JWT, Password hashing, HTTP, HTTPS, difference between GraphQL and REST, SQL queries, JS, NodeJS, 1 DSA question of DP.
918.      What do you know about dependency injection?
919.      I don't remember some questions, but here are a few which I remember. 1.Lifecycles on activity/fragment/views 2. Difference between val, const , and const val 3.MVVM 4. How would you have your data retained after the new launch 5. Architecture a new app based on requirements 6. Coroutine context 7. What is a lazy column in jetpack compose? 8. Three DS and algo problems(I don't remember the problems) 9. Kotlin scope functions 10. About my previous projects. 11. Toughest challenge faced by me? and more...
920.      Q: Are you familiar with JIRA Q: What is your development experience like etc. (fairly standard questions)
921.      What is Test driven design
922.      Q . Remove duplicate from array
923.      Binary search through an array, hash map questions, basic Data Structure and Algorithm problems
924.      1) Number of turns in a binary tree
925.      What are the stages in SDLC
926.      OOPs Conecpt Method Overloading and Overriding Primary and Foreign Key Java programs like prime number and reverse a string Create a table in SQL Insert a column in SQL
927.      * What is check point in SSIS ? * What is Clustered index?
928.      Describe an scenario which was challenging for you and how you did overcome it?
929.      easy leet code. BFS and DFS
930.      Linked tree , binary tree
931.      What is abstraction? Was is OOP?
932.      Refactor a badly written code, here is 400+ lines of requirements for you to understand how it should work
933.      "If a day on Planet A is 29 hours and a day on Planet B is 30 hours, what are the chances I was born on Planet A?"
934.      "What are the chances you have the same birthday as me?"
935.      "Imagine you had a 6-sided dice, and for each dot you get $1, what is the average money you'd make after X rolls?"
936.      Describe how would you create an API route
937.      Design a stack class which will return the most occurring number in the stack. If 2 numbers have the same count of occurrence then return the number which is at the top of stack. For this I was required to write the class with 2 methods push() & pop().
938.      Jane is taller than John, who is shorter?
939.      When did you f*ck up production ? And how did you solve it. explain O and D of SOLID
940.      Design parking lot with support for multi level parking using any language you want.
941.      Reverse a Doubly- Linked List?
942.      Design a WhatsApp System from scratch.
943.      Singletons Design patterns Oops concepts
944.      They request to create a small application with Laravel and Angular for create, update, read and delete data from MySql or PHP MyAdmin.
945.      What is threading in programming?
946.      Q: Tell me about a time where you didn’t deliver on something, and what was your reaction?
947.      Do you have experience in Docker?
948.      Cerate a docker container and write the config file
949.      -> Time complexities of various sorting algorithms?
950.      -> Explain the working of Merge Sort?
951.      -> Explain how grid system works in Bootstrap?
952.      -> Define how 'JOIN' works in SQL?
953.      -Where do you see yourself in 5 years? -What is a relational database? -What are the 4 pillars of OOP?
954.      Do you have experience with UDP/TCP
955.      What is SSR (Server Side Rendering)?
956.      the difference between the stack and heap
957.      What is polymorphism? What is inheritance
958.      Define the four pillars in OOPS.
959.      Why REST ? Why do we need REST?
960.      Oops concept - Abstract and Interface
961.      System Design: SQL vs. No-SQL databases, how to scale a database, UUID's, interaction between backend components, database sharding, etc. Coding: recursion, data structures, complexity, basic code optimization, etc. Cultural fit and managerial: dealing with low performers, managing style, description of my background, reasons to be a manager, etc.
962.      Group by in SQL?, How to create joins in SQL?
963.      what is buffer? what is latch?
964.      Given a sudoku board, return if the sudoku board is solved correctly
965.     string manipulation and dictionary.
966.     In my case I had to build a CRUD API. Not difficult but it takes time as you have to imagine a PRD setting (so having tests, proper abstraction, proper documentation on how to build etc...).
967.     Write a program that can reverse a list Do a code review - though this is very subjective as it was mainly about their personal likes/dislikes\
968.     Basic DSA, SQL and OOP questions.
969.     System related and opinions on current system.
970.     Codility, basic array manipulation questions. Technical interview. Doing replace templating on a string, which recieve a dictionary of keywords and values to replace. It was simple and something they might already did in one of their products.
971.     what is string? what is polymorphism? coding question of maximum sum array?
972.     Are you familiar with TypeScript
973.     Oops concept, database questions more related to joins
974.  Explain oop concept, sql, er diagram
Why you are using HTML5 in your projects.
Your experience working with sql, excel?
Write code for Reverse linked list.
Fully on Java OOPs concepts only.
Design the classes for an organism Prime numbers
Explain the OOPs concept? Why multiple inheritance cant be achieved in java? Why overriding is not possible in constructor?
Any trainings attended? What projects you have worked on?
2.Improve given code time complexity 3.SQL query
eventloop, trigger, singleton pattern, memoization, authorization, authentication,lazy loading, Streams, Buffers, SPA, overloading vs overriding, generics, http methods, interceptor, middleware
What is the MVC model
what is java and why java is oop ?
Write a code for a Given Roman numeral to convert it into an integer. Eg. Convert XXI or IX to it's equivalent integer number.
- Why Cambridge Intelligence? - Favourite programming languages? Why? - Design decisions related to your programming task - Lots of talk about past projects - what was it? what was learnt from it? what would you do differently? - Discussion around university courses - favourites? least favourites? tasks? teamwork?
What's a binary search tree?
Remove duplicate elements from array. Difference between overloading and overriding.
What is the difference between Table and View in SQL?
Build a react native registration screen with form validation
Core Java spring boot hibernate
SQL joins & logical scenario based questions, PBI detailed interview
MANUAL AND AUTOMATION Regression and retesting Bug life cycle
1. Find the Longest palindromic subsequence.
Basic Data structures Basic algorithms and puzzles
Reverse a string according to size of words
string manipulation and dictionary.
In my case I had to build a CRUD API. Not difficult but it takes time as you have to imagine a PRD setting (so having tests, proper abstraction, proper documentation on how to build etc...).
Different types of data structures
What prompted you to apply to Core specifically?
Spring boot annotations and corejava
30 mins of behavioral questions using STAR method. Questions on Java, OOPs concept, design concepts (very theoritical), SQL questions,questions on previous experience. No coding questions.
SQL questions -Joins,sub queries, etl and business.
- Describe your experience. - Describe a person/product that inspires you. - What is your expected salary?
Basic DSA, SQL and OOP questions.
Print a matrix in spiral order?
simple question on db design some short questions on Python leetcode-style questions on whatever language live-coding with React and Nodejs
Codility, basic array manipulation questions. 
Doing replace templating on a string, 
recieve a dictionary of keywords and values to replace. 
call by reference struct polymorphism
About AEM, questions about HTL, clientlibs project structure and authoring
DSA OOP DBMS All standard easy level questions. Two coding questions to be solved in 10 minutes each.
what is string? what is polymorphism? coding question of maximum sum array?
Are you familiar with TypeScript
Java, Scala, Modern Databases, Elastic Search, System Design
Given a string of parentheses tell if each one of them is properly closed, you have 3 types of parentheses '(, [, {'
Given two string tell if they contain the same characters and are of equal length (there was a word for this)
All question about SQL and kettle(job, transformation)
OOPS and basics and easy level coding questions
Star Pattern program , Armstrong number, palindrome program
write a program, given a range, x - y, and find the number of integers that is evenly divisible by 7 but not divisible by 3.
Write a polyfill for promise
Technical (domain based), questions from DS/DSA, programming languages, OOPS
write a program to find zeros between Binary number
All questions from profile and sharing rules, roles
Lightning bundles Lightning aura events and difference between events. Lightning data services, what parameters to set controller Difference between controller and helper Soql and fields to display according to user permission
Simple python programs on inheritance concepts and basic SQL queries
searching, design stack,linked list,heaps,proj discussion
Explain one of your past roles or project
what are the technologies used in angular? OOPS concepts Describe your projects html elements how to implement the code in browser
Test duration 90 mins No. of questions 4 questions "Questions Feel free to choose your preferred programming language from the list of languages supported for each question. There are 4 questions that are part of this test: Question Indexes Question Types Q1 - Q4 Coding Questions 21 languages allowed: c, clojure, cpp, cpp14, csharp, erlang, go, haskell, java, java8, javascript, julia, kotlin, lua, objectivec, perl, php, r, ruby, scala, swift" 1. Circular Printer 2. Balanced Array 3. Whole Minute Dilemma 4. Astronomy Board Game
They asked me to stand in front of all developers and talk about myself
What culture add can I bring?
What is your professional experience?
First, he asked me to brief about yourself and there was a long discussion about my projects and their applications. As I mentioned the github link for all the projects, he visited my profile and checked my repositories and asked about github and the tools I have used. Detect the loop in the linked list and then find the point from where the loop started.
1 string q, 1 dp, 1 array
Many questions about my current position, mindset and culture
- In depth python knowledge; mutability, immutability, syntax, lists/set/tuple difference, etc. - Flatten nested nested list.
more about oops and .net
What is difference between Interface and Abstract class
Languages, programming languages, or programming tools learnt and using
Data structures and System design interview.
Java, react, development, API , and about yourself
How will you handle the real time issues faced
Something related to Binary Seach or Two Pointer
Laravel basic question php basic question
They asked questions based on resume.
General hiring manager questions. System design question commonly asked. Non lc coding questions testing real coding experience, need to keep answering out loud and come up with test cases. One more on the caching side similar to redis and other question more api invocation/real time implementation.
On List<Car> cars : Use LINQ, Find cheapest car, most expensive car, average price, group by brand name and return a dictionary.
Reverse Linked list, binary tree traversal
Just read basics on interview preparation kit
Deep dive onto rails and databases
How would you design a system that had lot's of transactions which needed to be reflected on many clients as realtime as possible?
Hacker Rank,
Provide how you relate and can obtain the Amazon Leadership Principles to your life and role here. Customer Obsession. Ownership. Invent and Simplify. Are Right, A Lot. Learn and Be Curious. Hire and Develop the Best. Insist on the Highest Standards. Think Big.
Intuit Values (Typical Behavioral Questions) Graph traversing problem
Shortest path from leaf node to another leaf node in a binary tree.
-SQL query, join, grouping, aggragetion 2 algorithm questions
Q: Sort a linked list Q: Return ranges between an input list of ranges
How did you solve a hard problem in team collaboration? Give an example. What do you know about Service Oriented Architecture vs Microservices? What do you know about relational database? And NoSQL?
1. Design Interview: Design a game leaderboard with top K results. Assume there is an online game that's taking place, and you need to only build the dashboard that everyone is viewing. 2. Behavioral: They try to gauge your level here - so try to aim for an L5 - or explicitly state so. 3. Merge k sorted lists 4. Schedule matches between two sets of players where no two players have a re-match (play only once against each other)
Develop a full stack app in node, react, cypress and ts, docker, ci/cd and database
Tell me how you would design a food delivery app from start to finish.
Write an app to produce a report
Different question regarding job position
What are Keys and types of Keys in SQL?
Mostly based on what you had mentioned in your resume Question on REST operations PUT Vs POST How to pass params in path variable & also about query param How did you handle conflict of interest with your colleague Why REST?
Typical leetcode medium/hard, ie. bfs/dfs graph searching to find maximums/minimums, and object oriented stuff. Doing blind top 75 questions prepared me for the difficulty of this interviewing process.
Can you explain to me how to do matrix multiplication? Can you explain how you would implement matrix multiplication in a language of your choice? What's a volatile variable? What's a const? What's a const volatile?
Given a number, find the number of set bits
They asked me to code a card game.
A reverse engineered Caesar Cipher with twists on hacker rank.
they asked about alog, DS and industry best practices
Tell me about a time when you took a big risk that did not work out
Eg 1: Input: a1b10 Output: abbbbbbbbbb Eg: 2: Input: b3c6d15 Output: bbbccccccddddddddddddddd The number varies from 1 to 99.
different between HTTP and HTTPS
Java oops questions, polymorphism, different types of polymorphism
OOPS concepts, SQL, One programming language, Projects you did (prepare your resume)
2nd round Full Profile based analysis and few technical questions
she asked about program languages that i have experience with them.
remove duplicates from am array and sort it.
Importance of testing in the development cycle compared to analysis.
OOP related questions, the general stuff that you would expect from a junior/medior position interview.
Set up a linked list class and find if there are any duplicates
Linux, SQL, OOP, Primary key.
remove duplicates from array write a query joining two tables probability question bases on bayes therom traverse the array and list the duplicates OOPS concepts describe your project
Linked-list question (aced it) Find all 2x2 sub-arrays inside a larger array (didn't get to that, but I'm sure it's on Leetcode somewhere). Post-word: I got approached by Amazon twice since then. No thanks!
How could you help Lisk achieve its mission? What are custodians? What are market makers?
HTML, CSS, Js regarding styling and js built in functions
About project they asked me what was my contribution
Build a ledger from an predefined interface. Design a web crawler.
A single computer programming question based on denomination of currency
General behavioural question you are better off rehearsing off after research from google. Simple technical part except for the description above.
Write a program an array Sorting elements in array Query on DBMS
How do you communicate to the client if he doesn't understand a problem that you are raising?
Take-home assignment : display restaurants, delete and add one using Algolia search API.
What is OPP's concept? What is Object?
How you can handle broken links?
What is the order of constructing and deconstructing objects in cpp?
Hooks, closures
Are you a hardworking person ?
Algorithms and Software Architecture in some cases of e-commerce problems
Coding Question,Basics of Python and Django,MySQL Question
Coding, OOPS Concept, Basics of Python
Difference between List & Tuple
Start with core java like , oop concepts, Collection framework, Java8 features SpringBoot annotation like @RestController, @Autowired @Bean @Qualifier and more.
Basic OOPS concepts
1st round - OOPS, pointers, OS, DBMS, Logical Reasoning, output-based. 2nd Round - Linked List detect delete and reverse a string- both iterative and recursive—deep dive into Cpp concepts like friends function, typecasting, reference vs value, smart pointer, etc.
The interviewer asked me to introduce myself. Asked me what language do i know. Asked me about java and type code for matrices program. Then moved onto data structures asked about heapsort
What do you know about Apache Cassandra and NoSQL?
basic react interview questions and javascript basics
What are you previous projects? What data structure is used in API?
Write a Trigger on roll-up summary write a Trigger to restrict entering the date in the contact which is having lessthan the minimum_date and greater than maximum_date in related account record
Two DSA questions 1. for loop question 2. Flattening array without using inbuilt function.
Q: Mysql index. the difference of Innodb and MyISAM Q: data structure of redis and their implement
Describe the basic high-level architecture of a messaging application like WhatsApp & how will I implement it.
How to select elements from tree?.
Q.1) Give scenario where we can use abstract class and interface
Q. Creating polyfills for some methods, JavaScript variables, and their inner workings, sorting algorithm, and Advanced JavaScript concepts.
Build a factory floor diagram to move cars through an assembly line
Which technologies I’ve worked with and my education background
1. Design a DB API 2. Tic tac toe game on react 3. Query DB make joins and group data and count unique values in columns 4. Basic DS/Algo questions
Some graph questions, leetcode hard
questions were practical and and to the point. you have to find out an appropriate solution to them in an hour
First assessment: 1 sql, 2 algorithm, 1 javascript with html
What are the three ways to reduce page load time?
Related to database schemas and data analysis.
What is object oriented programming
What is hooks in react?
python oops concept. Django ORM, all model and structure of django
About Classes,Static,some Asynchronous Apex questions and Triggers
The Geofencing app that you have worked on - Unit Test - SOLID - Implement a new architecture that they want on the spot
Why apply with Setel? (They ask tricky questions here, please avoid answering anything related to better package, benefits, or salary, or else they will hunt you down.)
1. Tell me about yourself 2. Show me your project and explain 3. What is Semantic UI? 4. What is blockchain. NFT?
How do you keep up with technologies.
1. Tell me about yourself 2. Show some of your projects and explain different parts of it 3. What is semantic UI 4. What is blockchain, nft
Multi threading. Why are Locks used? Async and Await?
Started from oops and the difficulty level increases as the interview progress
Singleton pattern with example.
What is CTE?
what are SQL views? How is a view different from stored procedure and tables? Can views update data? Can views have indexes? What kind of data view reads?
How to increase WordPress website speed and optimize website performance? WordPress basic post types and Database related questions. Have you ever contributed to WordPress.org? How to protect WordPress websites from Hackers?
What is polymorphism in java?
Generic soft-skill/teamworking questions, "What is the difference between a linked list and an array", and the technical interview consisted of dissecting a specific project of mine that was listed on my resume.
2 String questions in the OA. 1 was easy. Other one was related to KMP algorithm. 1 heap question in interview
Atlassian wants to build a simple scheduling system that can execute one-off HTTP requests at a specified time. Consumers are internal Atlassian services only, and they may use this system to schedule requests to be executed in the future. For example: A consumer can schedule a request to https://testservice.com/api/items/_create to be executed on upcoming Sunday at 1am. So on upcoming Sunday at 1am the scheduling system must execute the HTTP request. Requirements: - Provide an interface for scheduling HTTP requests at a specified time. - Execute an HTTP request at specified time. - Initial release expects 10 scheduling requests per minute.
how to write trigger with map example
show me how to write a trigger on any object
show me how to see field history on object
show me how to create class, write soql query
show me how to add fields on page layout
Share your screen and show me how to add roll up summary field
Show me how to create visual force page
Show me how to assign case assignment rule, lead assignment rule
Apex Trigger involving parent - child relationship - Update a field on parent object which will contain average of all numeric values contained in some field of child object records.
Salesforce CPQ Product Rules and Price Rules along with multiple scenerios.
1. Past Experience 2. Leetcode Medium and Hard (LinkedList)
write PHP API call client with page token similar to google, also asked me to Write and API server and generate paging for the data set similar to google.
Hash table, aggregate a list of bank transactions so that each bank at most has 1 transaction with every other bank
What is singleton design pattern
Design a pizza shop using oops concept and code according to their requirements.
There were 2 coding questions. We spent 30 minutes on the first question, and the rest of the time on another question which I didn't finish.
Leetcode 
1. What is real life example of binary search ? 2. What is real life example of lambda functions in python ? 3. Why you choose python over java ?
They also asked about my knowledge of polymorphism
1.tell me about yourself 2.oops concept 3.method overloading & Method overriding 4.singleton pattern in java 5.difference between list and map 6.exception handling in java 7.table creation in mysql 8.how will manage multiple registration in mysql 9.explain about your projects
Appels REST difference http et https requete SQL sur un exercice (Left join) dis moi un peu sur selenium (comment instancier le driver , scroll, ...) les statuts de réponses Rest (404,400,...) Postman et variables Test design
Technical: Custom binding Extension functions String manipulation How to run 5 API calls and once all api calls are completes then proceed Questions around suspend functions and coroutine cancel. Data classes
What are Promises? what are callbacks? Tell me about binary Search?
Implement a linked list in which you can add, delete and view middle element in O(1) time
How did you fare in high school mathematics, physical sciences and computing? Which were strengths and which were most enjoyable? How did you rank, competitively, in them?
Software design Pattern . what is Singleton and observer design pattern
Ds algo: create a stack with o(1) min value
Lld: Design a photo download system in ios and swift
Create an Item listing application on xcoxd
Ds algo: find if paranthesis are balanced
How is Python language different from c++.
Directive, dependency injection ,Data binding,Observable, Angular features,explain the directives
Couple questions about computer science and general theory, and other questions about more concrete topics like advantages and disadvantages of different programming languages and their uses.
When do you use the `mutable' keyword?
What is hoisting in JS?
What is the difference between a stack and a heap?
Technical question pertaining to project.
Acid Property and how does it differ for NoSQL
Difference between TCP & IP
Explain OSI Layer
Questions on Sorting techniques
What happens in background during a http request
Advantage of tail over non tail recursion
What is tail recursion?
Q: WAP to print star pattern Q: WAP to sort list of integers without using inbuilt functions i.e. any sorting technique Q: Other spring boot & java generic questions
Questions about Data Architecture and Engineering. Concepts of handling data, Data Modeling and ETL Questions. 3 Hands on coding question. Did them in SQL.
Given a list of file paths, output a formatted directory structure
1. Difference between function expressions and function declaration. 2. What is hoisting? 3. How would you update a database with immutable records?
About core Java, Microservices, SQL, Collections
What is most difficult enhancement that you have done in the previous project
What's your favourite stack (frontend/backend) and why
MC round- design a music management system(Very simple) HLD-LLD- A notification management system DSA-Array of songs, play all songs in a random fashion infinite(or M ) number of times. Condition all songs in the current array to be played before starting the next cycle. Multithreading- Producer consumer problem, the interviewer will ask a lot of follow up questions, wants the most optimised way(CPU should be blocked only for producer or consumer thread at a particular time) Design pattern- You will be given a problem where you need to solve the situation via the correct design pattern(Very important) Database- Sharding, Indexing etc
Q: Write a program to find factorial of a number using recursion. Q: Wap to reverse a string using recursion. Q : Write a SQL query to find 3rd highest salary .
Q: Install docker, pull an image, run that image and hit a given URL using email, and API-key in headers to get next step question.
1. SQL 2. Abstraction 3. Multiple Choice 4. Problem to Solve
Longest Substring Without Repeating Characters
1. Difference between function expressions and function declaration. 2. What is hoisting? 3. How would you update a database with immutable records?
Practical exam was given - It was a PHP test.
Currency rate exchange system where actual rates are provided by a third party.
About core Java, Microservices, SQL, Collections
Q: Write a program to find factorial of a number using recursion. Q: Wap to reverse a string using recursion. Q : Write a SQL query to find 3rd highest salary .
automation and Functional Testing
API testing and Database testing
Difference between WCF and API
What are some Higher Order Array Methods and what they do ?
What's a class in Javascript ?
They asked me about callback, promisses, hooks , usestate
1.How to use generic? 2.Explain the process of creating a register page 3.Exceptation handling and current project discussion
Questions for the interview was : 1) Oops concepts in python 2) Django Framework workflow 3) Write a program of fibonacci series 4) Sql queries 1) Oops concepts in python 2) Django Framework workflow 3) Write a program of fibonnice series 4) Sql queries
1. Write a code to reverse a string 2. Opened Amazon.in and asked me to write XPath for elements on that page. 3.Difference between Abstract and Interface
The technical interview consisted of several themes - CPU bound vs I/O bound - async/multithreading in Python and effects of GIL - system design - slow HTTP attack on a reverse proxy
1. Bubble sort coding question using functions 2. Write programming logic to store your name using character pointer 3. Basic questions on data structures
Virtual DOM, Component Life Cycle, some JS questions, HackerRank calculator with testing
I have to do a python program for print a prime number
small project to develop api in go with mongodb.
Architecture, Database, CS fundamentals, Working experiences, and other...
do you work on integration?
oops concept SQL queries CRUD operations set method why $ used
Explain the types of joins in SQL
joints
Two cooks have a kitchen and require 30 minutes to bake a food what is the result?
Q: Are you interested in NFTs? Q: What experience do you have with .Net? Q: Experience with Go or C++?
What is inheritance? What is the way of inheriting variable of one class to any other class? What is Polymorphism?
Given 2 sorted arrays, merge them together, eliminate duplicates, and sort the result.
Find K Pairs with Smallest Sums, Intersection of Two Arrays, Longest Increasing Subsequence, Longest Substring Without Repeating Characters, etc.
Solid principals ? Design patterns? DDD concepts? Message brokers ?
Used a third party coding test site, two questions and 1 hour to solve them.
Closures, Scope, Box Model, REST
What is the Observer Pattern
Q1. What technologies you have worked on?
Code for frequency of elements in the list min and max value from the list basic data types,oops concept question MySQL based questions
Did u have any experience developing Micro Services app?
Explain spring MVC flow and architecture
Whats was your biggest achievement ?
What are SOLID principles, and design patterns? Define and give an example of the Singelton pattern. Abstract classes and interfaces.
LLD for a learning platform.
covered some SQL concepts, Designs Patterns, Talked about your current role - are you familiar with Kanban - are you up-to-date with recent technologies? some behavioral questions based on scenarios.
What is the role play for seek() and Tell()
Red black tree map implementation.
Did u have any experience developing Micro Services app?
covered some SQL concepts, Designs Patterns, Talked about your current role - are you familiar with Kanban - are you up-to-date with recent technologies? some behavioral questions based on scenarios.
1. What are the primitive data types in java? 2. What are the collections in java? 3. What does the TreeSet do and how different it is from the TreeMap. 4. Difference between list and set?
Explain about Binary searching in Data structures
Polymorphism, computer basics , joins,structures,class, hashes.
designing APIs, linked list implementation, SQL concepts, OOPS questions, some deep IAM questions
Linked List ,Graph,Tree, Bit Manipulation, Array, Strings oops concept, dbms concept, Project discussion, ontime performance and many more.. In short the process was tough and it should not be taken litely. They will judge in every minute for whatever the single word you had spoken. So maintain the well communication
Micro services architecture Traditional C# questions with SQL queries
number of set bits in a number
SQL question: Triggers,SP and Functions SSIS: Transformations and scenario-based question
What do you know about Functional and Class components.
3 coding questions in Codility.
SOLID. Design Pattern. Where did you use them.
Algorithms, Design patterns, Networking, Algorithm complexity
What would a REST API for a bookshelf look like?
Common data structure and design questions
Basic OOPs questions and Mysql query
What is overloading and overwriting?
What is the difference between a Super Class and a Sub Class?
Basic Testing Concepts on Technical Round. Agile, API testing, Functional Testing, and scenario-related questions.
Q: Explain what a hashmap is and the implementation. Q: What is the difference between a set and a list? Q: Design a computational model of an elevator. Q: Analysing Java code and explaining bugs, or where efficiency could be improved.
It's been several weeks so I may not remember everything, but it's the same MS Paint clone that others have shared here. No user interface is required, just a few functions such as paint and undo. You should be able to undo multiple times. The input is an array of strings which represent individual pixels' colors, and the output is the new array of strings after the change (paint or undo) has been made.
Q: What is polymorphism? Q: What does it mean to overload a method, and why would you need to do it? Q: What is your experience with working in teams?
Something related to architectures and git
Round 1: 1. Merge intervals 2. Palindromic linked list Round 2: This was supposed to be a LLD round. The hiring manager began my interview questioning my job switches in a sarcastic way. I felt very uncomfortable at this point and i could sense she had made her mind to reject me for my job hops and did the interview for namesake. She just threw lots of theoretical questions to me like difference between POST and PUT, monolithic vs microservice, docker etc. to pass time of 1 hr. Very disappointed with the process .
Ho do you manage your tasks?
What computer language you like to work on?
1. How to design a Applicant Tracking System? 2. How to design a messaging system with different failover scenarios. 3. Optimize factorial program There were few more designing questions which I don't remember but those were not too hard.
Can you explain yourself please?
What motivates you to get up every day/do this kind of science?
Why did you choose software engineering?
Q: Have you used <tech>?
First non-repeating char (in single pass) Merge two sorted arrays Merge k sorted arrays Is a given tree is BST Design a half way Queue in optimized way.
What is method over loading and methods overriding?
 Qual a diferença entre REST e RESTFull ?
 Write the fibonacci sequence using only one loop?
Is smart work better than hard work ? Hard Work Vs Smart Work
CI/CD REST API MVC and other backend basics ...
How would you rate your lang skills
Why are you leaving your previous company
To find permutations for non intersecting chords using n points on a circle.
Question to to detect and remove cycle from linked list.
Resume round 2 Question rather than being focused on the web core concept and developer resume based , were more focused on the devops like CI/ CD pipelines , docker and Jenkins. How to optimize ur CI/ CD pipelines ina project
Round 1 - DSA and problem solving Round 2 - Java and OOPS fundamentals
Jenkins installation method Agent installation method.
Longest possible sequence in the given array
Q: Describe a time you overcame a difficulty
1. Where do you see yourself in next five years?
Is there something in your career that made you feel like it was impossible to move forward?
How would you design a data lake for a customer using AWS.
It was a cloud architecture question.
Questions on Java and rest webservices. Questions based on experiences.
What is the 8th power of 2 Binary Tree search
MySQL y OOP, entre otras .
Design a service which pulls IP Blocklist data from GitHub and expose an endpoint which returns Blocklists an IP address is contained in.
was asked to design a rate limiter
difference between a list and array
Cognitive Ability Test, similar to IQ test. Has questions about pattern recognition, grammar, simple maths and more.
System Design Q: Why did you use this design? Q: What is the exact scope of the design? HR Q: How can you work smoothly with a new team-member? Q: How can you make a bug-free code? What kind of effort does the development process make it bug-free code? Q: Amazon Interview Style question. Let me~ *Every Interview Session contain. 5min introduce myself time.
what is the runtime of the following code? what is the difference between polymorphism and inheritance? Why did you choose mobile app development? why did you choose Alarm.com
what is multithreading in os
What was your relevant experience
What was the most complicated project you've ever worked on?
Build binary search tree (including nodes), build program to make every third word uppcase
1. Code a function from javascript _loadash library 2. Pseudocode for a parser 3. Graph Problem 4. Design a react component
What are your interests in software development?
why do you think you will make a good fit?
Have you programmed with TCP/IP protocols before?
Create 9 boxes and add green background colour when clicked
Design patterns and implement one in the interview and explain why.
Simple programming question for pair programming, system design, examples of ways you have demonstrated leadership in the past
With a very simple incrementing variable, what happens when we add threads to the program? How can we ensure things work correctly? After being shown any number of naive approaches to locking, which ones would work?
Implement the backend for a Wordle clone
Design the road incident reporting feature of Waze.
If Martians existed and had to request data from Earth, how could we reduce latency of requests. If we still see high or slightly higher p99s, what might be the cause?
Implement an algorithm to find the square root of a number. How do you make it more efficient.
Given a list of words, return groupings of all palindromes.
Design a dictionary API and design a race circuit leaderboard.
Domain knowledge
Make a triangle pattern given below. * ** *** ****
Q: Tell us about your experience with the SDLC
1. Bubble Sorting 2. Hibernate
About OOPS concepts and PHP basic
1. Event Loop in node js 2. How do APIs interact from backend to frontend. 3. Question related to the technology stack I have mentioned in my resume.
get array of digit and change it to integer then sum reverse digit
Factorial program in both first class and with recursion.
Introduce yourself. College projects? How you used your technical knowledge in real world? OOps concepts.
How do you implement your error handling?
Take home test - racing robots. Multi-threaded OO design project. Print from 0 to n without using any type of loop and also write a function to print up to n and then back down to 0 (use recursion). Looking at a code example of what was supposed to be an immutable class but having to explain why some of the internals could still be changed after construction due to object references and then saying how to fix it.
implement logic for tick-tac-toe and phonebook
Q. Oops Concepts. Q. Does java supports multiple inheritance ? If yes then how? Q. Interface related output programming questions. Q.is it possible to have same methods on 2 different interfaces? Q. Internal working of Hashmap. Q.Explain any Sorting Technique you know. Q. Stack and Queue Q. We have a binary number 1011 stored in a linked list, and we want its equivalent decimal in output(11).Write a program for it. Q.We have an array of numbers, write a program which returns the non repetitive number. Q.write a function to check if a string is a palindrome. Q.Android LifeCycle Q. Android Application Components. Q.Define a scenario where onCreate is called but on resume not called. Q. Define a scenario where onStop called but onPause not called. Q.what are fragments Q.MVVM Q.How can we call the activity methods in fragments Q. What are Kotlin Extensions?Why do we need them? Q. What are data classes in kotlin? Q. What is companion object in kotlin?How can we use it in our java code?
If I prefer backend or frontend
Q: What was the reason you got into tech?
Problem about hash map data structure.
So tell me What is SQL?
Common intersection point of Linked List
Basic programming question. And sql queries.
Dive deeper into my previous intern experience.
Describe your project. Favorite core subjects.
What would you do if you had two tight deadlines and weren't able to meet them.
How to design a sample system. How do you communicate with the team in different situations.
Design a deck of cards, leadership principles, system design of a car dealership, DFS question
What are the differences between function and procedure in sql
Coin change binary tree (LC Hard)
Here is a link to an empty white board. Without any reference, write out the data structure for perfectly mapping a 3 dimensional object suspended in space. Give the backend engineers the data structure you require to render a suspended 3 dimensional object. The object dimensions are assumed to be the same. Oh yeah, and the object dimensions are assumed to always change. Assume they know everything. What would you write as a data structure to fill them in on what they don't know? Write this out on the whiteboard with no reference to anything I am talking about.
Solidity try catch syntax and the outcome
Explain Java ConcurrentHashMap in depth, the implementation, volatile in JVM
Whats the different between storage, memory and calldata
Multiple Inheritance in Solidity, the expected outcome
What is Minimum viable proxy eip1167
Call vs Delegate call, and the use case
Something related to hashing and maps
How would you improve a technical solution
1. Parse a bizarre string 2. Parse a even more bizarre string
Tell me about a time you had conflict with another person and how you resolved it.
Based on shell scripting and few ds, dont really remember the questions but it was basic.
Describe your experience with SASS.
Every word on your resume becomes a question
Gave a case study and was asked to present it using my experiences and learning.
What is Oriented Object Programming?
Python basics problem, django workflow,ORM
Python, POO, .NET Json Aptitudes
how to implement a command
Tree Linkedlist Design Array Strings
Have you worked with any databases such as Django or flask.
Some Api library call and fetching data
Q: What is polymorphism (as it relates to object-oriented programming)?
Reasons for entering the field
A dynamic programming question. Graph theory
The phone call was with the CTO and was pretty conversational
Routing, Layer2/3 questions and find no. of hosts/subnets from Ip and mask
What are you looking for in you new job?
What are the company's values?
They send a test case which you need to hand in your solution in 4 hours. the expectation is to solve the algorithm in an efficient way.
write SQL query for given scenario DSA
Q: Find the shortest distance to a character in a string
Q: Find the longest palindromic substring of a string.
Q: Find the longest palindromic substring of a string.
A data structure question
what is event flow?
Basic oops concepts questions and few scenarios based questions.
Main question: try to model Amazon online store by uaing Data structures, DB, search and index functionality - how will you find an item by a category, price, etc.
Warm up question about an array from cracking the coding interview (literally)
How to iterate through a binary tree
How do you measure your success on a daily basis?
how to add two no without add operator ?
Tell me about a problem you encountered when working on your project and how you solved it.
Tell me about one challenge you faced/ your biggest achievement
What is the difference between optimistic and pessimistic locking? What is the difference between git rebase and git merge?
What is a variable? What is an object?
Which is your favourite programing language and why you choose it?
What relative experience do you have?
Is it possible to call batch from batch
Where do you live? Do You know to drive? Tell me about yourself.
describe what the routing does in an express server. what is a waterfall working approach vs agile. what are the benefits using the stack that you chose. is mongoose a db? what is the difference between mongodb and sql? what are the benefits of these? what is a RESTful API? what is a monolith app? what is a micro service?
What management style do you prefer to work under?Java, oops, microservices, situation based questions
1.Difference between DELETE and TRUNCATE 2.cat command usage 3.Command to find hidden files in unix 4.Remove white spaces in a file in unix 5.SQL query to find 5th highest salary
1.What happens if we pass null values to rollup and scan components? 2.Replicate usage 3.Difference between replicate and broadcast 4.Left Outer Join 5.Dedup sort in abinitio
Which component breaks component parallelism
Explain what are different types of parallelism
Difference between output index and output indexes
Difference between Partition by key and partition by round robin
I has an assessment to develop over a week and a live white board challenge.
What is the most interesting technological development
Which methodology you are following in your organization?
db migrations, testing, architecture design, etc etc
what is Concurrent hashmap collection framework one coding question on array
What do you know about The Composable Architecture?
What subjects I studied. What projects I developed.
What do you feel about TDD and do you like writting Unit tests for your code?
Technical related concepts and aws realted concepts
Fetch from fake api and send errors
Basic questions related to the domain knowledge
Apart from the personal questions that are asked to know me better, there were some cognitive questions to understand the way I think.
Leetcode-like interview questions. You can choose a preferred programming language.
What is the best possible consistency of a development team you could think of?
Patterns and some examples . Palindrome
Weighted multilevel graph questions with implementation using dynamic programming
How would you implement scanf and printf, if you are part of a team that is developing a new language.
In my case as I was giving an interview for a full stack developer. They asked all stack questions (JavaScript, C#, and SQL). Also, they check data structure and algorithm
- Designing Questions (design patterns, oop) - some Database related questions (indexing..etc) - JS coding challenge - Microservices questions
C++ ,C,QS,Linked list like reverse a linked,implement using stack, questions from array like 2nd largest element,Database(simple ones),OS,questions on projects too. The Questions of programming are basic,they just check your concepts and give you time to think during the interview
Coding questions 1)reverse string questions of any kind
SQL Queries , Python OOPs, Big data basic, Project
What is the difference between a list and a tuple in python?
How to reverse a linked list
System design for an app
System design in a virtual whiteboard.
Max sum without adjacent elements
About my previous project and questions from SQL and JAVA
What do you do when you get disappointed?
Q; asked questions based on my experience and projects
Assignment questions: 1. Creating a python API for bulletin system 2. Creating a CI/CD pipeline in a docker environment and a celery task on python for message queue systems.
Culture fit and basic javascript questions.
What are the responsibilites of the Operating system
Two sum, system lock, bit manipulation
1) Stack/queue problems on leetcode 2) java dependency injection 3) java garbage collection
How do you design a queue based logging system.
How to use Polymorphism and Inheritance to make the code runnable?
How to add a method to the function without modifying the original class?
1. What is difference between comparator and comparable 2. Explain this statement System.out:: println 3. How's d you filter out elements using steams? 4. What are new features of Java 8
What would you do if you hit a dead-end?
First codesignal round was a standard OA, the second one involved interacting with a codebase and making REST API calls
What was your greatest accomplishment in high school?
How do you construct a promise from scratch?
why you choose laravel for backend?
What are different types of casting?
what is framework , debugging and based on the language you know, questions are framed
1. DBMS 2. Javascript 3. Project Discussion
Model write up and essay
How can you handle unwanted situations in your team?
what are three good and bad things your friends would say about you
Hashmap working
what is AWS EC2
Project related questions and cv based
1. Explain Agile 2. what is Spike 3. What is difference between SOAP & REST API 4. What is Regression Testing
OA coding questions: delete an item in a Linked list air invaders counting bits creating a binary search tree
How do you initialize pages in Page Object Model?
Some String and HashMap based Java coding challenges.. Refer easy sections of LeetCode.com
Questions on different types of API request headers like what kind of response is expected, and what is security tag talking about?
How do you perform API testing in your project?
What is the REST API?
How the HashMap is implemented?
Q : What is the output of the following code? #include <stdio.h> int main() { int x=5; if(x==5){ if(x==5)break; printf(“Hello”); } printf(“Hi”); }
Reverse a string, read from file
Question on stack and queues.
Linked list, hash map, data structures
What was your biggest failure?
Quick sort, priority queue, sweep line, sliding window
Reverse an array except for the beginning and end
Real Examples with Psuedo code
Merge Sort, quick Sort, DSA
- Java from basics to advanced concepts with programs. - Data Structures - Multi threading - Spring Boot Basics and Rest API with sceneries given to write API
Tell me about yourself, my strength and weakness
 Salary expectations
 How many types of array are there in PHP?
What are the ways to define a constant in PHP?
What data did you use to make your decisions on the project?
What is 1 thing you would like to learn more about, and possibly talk about in a meeting
How would you design an app and database for a Vet Office?
start from a small scale system and grow to large scale system
few SQL scenario
basic Talend audit n error handling scd type warehouse questions
1. quick questions. around OS, network, databases. 2. Implement delayed scheduler 3.top k posts trending on Linkedin.
Inquired about my developer background.
Who are you as a person? What ambitions do you have?
Is javascript synchronous or asynchronous?
Have you ever fired anyone? Follow up questions. Have you ever promoted anyone? Follow up questions. String manipulation coding round. How would you choose a leader for your team?
Q. How to build binary tree in sorted.
C questions, microcontrollers, last experience
Automate the login process using your local env.
Self introduction, Former working experience. Coding challenge
Oops concept, polymorphism, abstraction, join
How to solve some SQL Problems
Automate the login page, use your local environment
How to reverse a binary tree.
1. Java Design Pattern 2. Java Streams API
Implement a function to tell if a graph is bipartite. Implement an image convolution operator.
Binary tree search modification question
Lifecycle method, Pure Component, Hooks concepts, Es6 concepts
One simple for example: difference between tuples and lists in python.
They asked me to design database structure for Charity funding application ?
How MVC arquitecture is organized?
Write a Depth First Search Function
Framework knowledge and Core PHP
Is javascript synchronous or asynchronous?
Q. How to build binary tree in sorted.
Automate the login process using your local env.
Oops concept, polymorphism, abstraction, join
How to solve some SQL Problems
How to reverse a binary tree.
1. Java Design Pattern 2. Java Streams API
Binary tree search modification question
Lifecycle method, Pure Component, Hooks concepts, Es6 concepts
Pattern star and number type
How MVC arquitecture is organized?
Framework knowledge and Core PHP
Coding design pretty much standard stuff
1: Code up a web crawler. 2: OOD for a log system.
Which difficulties did you encounter in previous jobs? How did you solve them?
What is the difference between git rebase and git merge?
Basic TDD design questions and OOPs concepts
Q: Basic relational database questions like indexing and many to many relations.
What are your strengths and weaknesses?
Count number of substring occurrences
Introduce about yourself What is data encapsulation
What does a special set of tags <?= and ?> do in PHP?
What’s the difference between include and require?
I am trying to assign a variable the value of 0123, but it keeps coming up with a different number, what’s the problem?
Would I use print "$a dollars" or "{$a} dollars" to print out the amount of dollars in this example?
How do you define a constant?
How do you pass a variable by value?
Will comparison of string "10" and integer 11 work in PHP?
When are you supposed to use endif to end the conditional statement?
Explain the ternary conditional operator in PHP?
How do I find out the number of parameters passed into function?
 **[⬆ Back to Top](#table-of-contents)**

What is PHP?
PHP is a server side scripting language commonly used for web applications. PHP has many frameworks and cms for creating websites.Even a non technical person can cretae sites using its CMS.WordPress,osCommerce are the famus CMS of php.It is also an object oriented programming language like java,C-sharp etc.It is very eazy for learning

What is the use of "echo" in php?
It is used to print a data in the webpage, Example: <?php echo 'Car insurance'; ?> , The following code print the text in the webpage

How to include a file to a php page?
We can include a file using "include() " or "require()" function with file path as its parameter.

What's the difference between include and require?
If the file is not found by require(), it will cause a fatal error and halt the execution of the script. If the file is not found by include(), a warning will be issued, but execution will continue.

require_once(), require(), include().What is difference between them?
require() includes and evaluates a specific file, while require_once() does that only if it has not been included before (on the same page). So, require_once() is recommended to use when you want to include a file where you have a lot of functions for example. This way you make sure you don't include the file more times and you will not get the "function re-declared" error.


Differences between GET and POST methods ?
We can send 1024 bytes using GET method but POST method can transfer large amount of data and POST is the secure method than GET method .

What is the purpose of the superglobal variable called $_SERVER ?
$_SERVER is an array and it holds the information about paths, headers, and script locations.

How to Detecting request type in PHP ?
By using $_SERVER['REQUEST_METHOD'] method

How to declare an array in php?
Eg : var $arr = array('apple', 'grape', 'lemon');

How can PHP interact to Javascript ?
PHP cannot interact with javascript directly, since php is server side programming language when javascript is a client side programming language. However we can embbed the php variable values to a javascript code section when it complile at the server or javascript can communicate to a php page via http calls

NB: Javascript can run at the server side as well using Node.js Server

How to manipulate image files using php ?
GD is library that providing image manipulation capabilities to php, so that we can do so many things such as crop, merge, change grayscale and much more with GD functions

How to manipulate video files using php ?
There is no inbuilt library available in php, However there are some open source libraries that providing these features

FFmpeg is a complete, cross-platform solution to record, convert and stream audio and video. We can install this extension in php and use to do variety of tasks

What is cron jobs ?
Cron jobs are scheduled tasks, executed on regular time intervals set by the developer. They work by running preferred scripts. We can set the time intervals for running these scripts. Its not a part of php compiler, We have several ways to do this based on the platform or the hostign control panel type

How to sent a POST request from php ( Without using any html ) ?
You could use cURL, that allows you to connect and communicate to many different types of servers with many different types of protocols such as http, https, ftp etc.

How to create a directory if it doesn't already exist ?
<?php
if (!file_exists('path/to/directory')) {
    mkdir('path/to/directory', 0777, true);
    }
?>
How to delete an element from an array ?
If you want to just delete a single element you can use unset() or alternatively array_splice().

unset() method won't change array key when array_splice() method change the array keys automatically

What is the use of 'print' in php?
This is not actually a real function, It is a language construct. So you can use with out parentheses with its argument list.
Example print('PHP Interview questions');
print 'Job Interview ');

What is use of in_array() function in php ?
in_array used to checks if a value exists in an array

What is use of count() function in php ?
count() is used to count all elements in an array, or something in an object

What's the difference between include and require?
It's how they handle failures. If the file is not found by require(), it will cause a fatal error and halt the execution of the script. If the file is not found by include(), a warning will be issued, but execution will continue.

What is the difference between Session and Cookie?
The main difference between sessions and cookies is that sessions are stored on the server, and cookies are stored on the user's computers in the text file format. Cookies can't hold multiple variable while session can hold multiple variables..We can set expiry for a cookie,The session only remains active as long as the browser is open.Users do not have access to the data you stored in Session,Since it is stored in the server.Session is mainly used for login/logout purpose while cookies using for user activity tracking

How to set cookies in PHP?
Setcookie("sample", "ram", time()+3600);

How to Retrieve a Cookie Value?
eg : echo $_COOKIE["user"];

How to create a session? How to set a value in session ? How to Remove data from a session?
Create session : session_start();
Set value into session : $_SESSION['USER_ID']=1;
Remove data from a session : unset($_SESSION['USER_ID'];

what types of loops exist in php?
for,while,do while and foreach (NB: You should learn its usage)

Note:-

MySQLi (the "i" stands for improved) and PDO (PHP Data Objects) are the MySQL extensions used to connect to the MySQL server in PHP5 or verions, MySQL extension was deprecated in 2012.

MySQLi only works with MySQL databases whereas PDO will works with 12 other Database systems

I recommend PDO because, if you want to choose another database instead of MySQL, then you only have to change the connection string and a few queries. But if you are using MySQLi you will need to rewrite the entire code

How to create a mysql connection?
Example (PDO)
<?php
$servername = "localhost";
$username = "username";
$password = "password";

try {
    $conn = new PDO("mysql:host=$servername;dbname=myDB", $username, $password);
    // set the PDO error mode to exception
    $conn->setAttribute(PDO::ATTR_ERRMODE, PDO::ERRMODE_EXCEPTION);
    echo "Connected successfully";
    }
catch(PDOException $e)
    {
    echo "Connection failed: " . $e->getMessage();
    }
?>

Example (MySQLi Object-Oriented)
<?php
$servername = "localhost";
$username = "username";
$password = "password";
$dbname = "myDB"; // Optional

// Create connection
$conn = new mysqli($servername, $username, $password, $dbname);

// Check connection
if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
}
echo "Connected successfully";
?>

Example (MySQLi Procedural)
<?php
$servername = "localhost";
$username = "username";
$password = "password";
$dbname = "myDB"; // Optional


// Create connection
$conn = mysqli_connect($servername, $username, $password, $dbname);

// Check connection
if (!$conn) {
    die("Connection failed: " . mysqli_connect_error());
}
echo "Connected successfully";
?>

What are prepared statements?
A prepared statement or a parameterized statement is a feature used to execute the same SQL queries repeatedly with high efficiency. It consists of two stages: prepare and execute. Prepared statements reduce parsing time because preparation on the query is done only once while the statement is executed multiple times. It is very useful against SQL injections because parameter values won't alter objective of the statement.

How to execute an sql query? How to fetch its result ?
Example (MySQLi Object-oriented)

$sql = "SELECT id, firstname, lastname FROM MyGuests";
$result = $conn->query($sql); // execute sql query

if ($result->num_rows > 0) {
    // output data of each row
    while($row = $result->fetch_assoc()) { // fetch data from the result set
        echo "id: " . $row["id"]. " - Name: " . $row["firstname"]. " " . $row["lastname"]. "<br>";
    }
} else {
    echo "0 results";
}

Example (MySQLi Procedural)

$sql = "SELECT id, firstname, lastname FROM MyGuests";
$result = mysqli_query($conn, $sql); // execute sql query

if (mysqli_num_rows($result) > 0) {
    // output data of each row
    while($row = mysqli_fetch_assoc($result)) { // fetch data from the result set
        echo "id: " . $row["id"]. " - Name: " . $row["firstname"]. " " . $row["lastname"]. "<br>";
    }
} else {
    echo "0 results";
}
Example (PDO)

Method 1:USE PDO query method
$stmt = $db->query('SELECT id FROM Employee');
$row_count = $stmt->rowCount();
echo $row_count.' rows selected';

Method 2: Statements With Parameters
$stmt = $db->prepare("SELECT id FROM Employee WHERE name=?");
$stmt->execute(array($name));
$rows = $stmt->fetchAll(PDO::FETCH_ASSOC);
Write a program using while loop
<?php
$x = 1;

while($x <= 5) {
    echo "The number is: $x <br>";
    $x++;
}
?>
How we can retrieve the data in the result set of MySQL using PHP?
MySQLi methods
1. mysqli_fetch_row
2. mysqli_fetch_array
3. mysqli_fetch_object
4. mysqli_fetch_assoc
PDO methods
1. PDOStatement::fetch(PDO::FETCH_ASSOC)
2. PDOStatement::fetch(PDO::FETCH_OBJ)
3. PDOStatement::fetch()
4. PDOStatement::fetch(PDO::FETCH_NUM)
What is the use of explode() function ?
Syntax : array explode ( string $delimiter , string $string [, int $limit ] );
This function breaks a string into an array. Each of the array elements is a substring of string formed by splitting it on boundaries formed by the string delimiter.

What is the difference between explode() and str_split() functions?
str_split function splits string into array by regular expression. Explode splits a string into array by string.

What is the use of mysqli_real_escape_string() function?
It is used to escapes special characters in a string for use in an SQL statement

Write down the code for save an uploaded file in php.
<?php
if ($_FILES["file"]["error"] == 0)
{
move_uploaded_file($_FILES["file"]["tmp_name"],
      "upload/" . $_FILES["file"]["name"]);
      echo "Stored in: " . "upload/" . $_FILES["file"]["name"];
}
?>
How to create a text file in php?
<?php
$filename = "/home/user/guest/newfile.txt";
$file = fopen( $filename, "w" );
if( $file == false )
{
echo ( "Error in opening new file" ); exit();
}
fwrite( $file, "This is a simple test\n" );
fclose( $file );
?>
How to strip whitespace (or other characters) from the beginning and end of a string ?
The trim() function removes whitespaces or other predefined characters from both sides of a string.

What is the use of header() function in php ?
The header() function sends a raw HTTP header to a client browser.Remember that this function must be called before sending the actual out put.For example, You do not print any HTML element before using this function.

How to redirect a page in php?
The following code can be used for it, header("Location:index.php");

How stop the execution of a php scrip ?
exit() function is used to stop the execution of a page

How to set a page as a home page in a php based site ?
index.php is the default name of the home page in php based sites

How to find the length of a string?
strlen() function used to find the length of a string

what is the use of rand() in php?
It is used to generate random numbers.If called without the arguments it returns a pseudo-random integer between 0 and getrandmax(). If you want a random number between 6 and 12 (inclusive), for example, use rand(6, 12).This function does not generate cryptographically safe values, and should not be used for cryptographic uses. If you want a cryptographically secure value, consider using openssl_random_pseudo_bytes() instead.

what is the use of isset() in php?
This function is used to determine if a variable is set and is not NULL

What is the difference between mysqli_fetch_array() and mysqli_fetch_assoc() ?
mysqli_fetch_assoc function Fetch a result row as an associative array, While mysqli_fetch_array() fetches an associative array, a numeric array, or both

What is mean by an associative array?
Associative arrays are arrays that use string keys is called associative arrays.

What is the importance of "method" attribute in a html form?
"method" attribute determines how to send the form-data into the server.There are two methods, get and post. The default method is get.This sends the form information by appending it on the URL.Information sent from a form with the POST method is invisible to others and has no limits on the amount of information to send.

What is the importance of "action" attribute in a html form?
The action attribute determines where to send the form-data in the form submission.

What is the use of "enctype" attribute in a html form?
The enctype attribute determines how the form-data should be encoded when submitting it to the server. We need to set enctype as "multipart/form-data" when we are using a form for uploading files

How to create an array of a group of items inside an HTML form ?
We can create input fields with same name for "name" attribute with squire bracket at the end of the name of the name attribute, It passes data as an array to PHP.
For instance :

<input name="animal[]" id="cat" />
<input name="animal[]" id="rat" />
<input name="animal[]" id="lion" />
<input name="animal[]" id="snake" />
Define Object-Oriented Methodology
Object orientation is a software programming methodology that is based on the modeling a real world system.An object is the core concept involved in the object orientation. An object is the copy of the real world enity.An object oriented model is a collection of objects and its inter-relationships

How do you define a constant?
Using define() directive, like define ("MYCONSTANT",150)

How send email using php?
To send email using PHP, you use the mail() function.This mail() function accepts 5 parameters as follows (the last 2 are optional). You need webserver, you can't send email from localhost. eg :

<?php
mail($to,$subject,$message,$headers);
?>
mcrypt_encrypt :- string mcrypt_encrypt ( string $cipher , string $key , string $data , string $mode [, string $iv ] );
Encrypts plaintext with given parameters
How to find current date and time?
The date() function provides you with a means of retrieving the current date and time, applying the format integer parameters indicated in your script to the timestamp provided or the current local time if no timestamp is given. In simplified terms, passing a time parameter is optional - if you don't, the current timestamp will be used.

How to find the number of days between two dates ?
<?php
$now = time(); // or your date as well
$your_date = strtotime("2010-01-31");
$datediff = $now - $your_date;
echo round($datediff / (60 * 60 * 24));
?>
How to convert one date format into another in PHP ?
<?php
$old_date = date('l, F d y h:i:s'); // returns Saturday, January 30 10 02:06:34
$old_date_timestamp = strtotime($old_date);
$new_date = date('Y-m-d H:i:s', $old_date_timestamp);
?>
What is the use of "ksort" in php?
It is used for sort an array by key in reverse order.

What is the difference between $var and $$var?
They are both variables. But $var is a variable with a fixed name. $$var is a variable who's name is stored in $var. For example, if $var contains "message", $$var is the same as $message.

What are the encryption techniques in PHP
MD5 PHP implements the MD5 hash algorithm using the md5 function,
<?php
$encrypted_text = md5 ($msg);
?>
What is the use of the function htmlentities?
htmlentities Convert all applicable characters to HTML entities This function is identical to htmlspecialchars() in all ways, except with htmlentities(), all characters which have HTML character entity equivalents are translated into these entities.

How to delete a file from the system
Unlink() deletes the given file from the file system.

How to get the value of current session id?
session_id() function returns the session id for the current session.

What are the differences between mysqli_fetch_array(), mysqli_fetch_object(), mysqli_fetch_row()?
Mysqli_fetch_array Fetch a result row as an associative array, a numeric array, or both.
mysqli_fetch_object ( resource result ) Returns an object with properties that correspond to the fetched row and moves the internal data pointer ahead. Returns an object with properties that correspond to the fetched row, or FALSE if there are no more rows
mysqli_fetch_row() fetches one row of data from the result associated with the specified result identifier. The row is returned as an array. Each result column is stored in an array offset, starting at offset 0.
Why we shouldn't use mysql_* functions in PHP?
Is not under active development
Is officially deprecated as of PHP 5.5 (released June 2013).
Has been removed entirely as of PHP 7.0 (released December 2015)
What are the different types of errors in PHP ?
Here are three basic types of runtime errors in PHP:

1. Notices: These are trivial, non-critical errors that PHP encounters while executing a script - for example, accessing a variable that has not yet been defined. By default, such errors are not displayed to the user at all - although you can change this default behavior.
2. Warnings: These are more serious errors - for example, attempting to include() a file which does not exist. By default, these errors are displayed to the user, but they do not result in script termination.
3. Fatal errors: These are critical errors - for example, instantiating an object of a non-existent class, or calling a non-existent function. These errors cause the immediate termination of the script, and PHP's default behavior is to display them to the user when they take place.
what is sql injection ?
SQL injection is a malicious code injection technique.It exploiting SQL vulnerabilities in Web applications

What is x+ mode in fopen() used for?
Read/Write. Creates a new file. Returns FALSE and an error if file already exists

How to find the position of the first occurrence of a substring in a string
strpos() is used to find the position of the first occurrence of a substring in a string

What is PEAR?
PEAR is a framework and distribution system for reusable PHP components.The project seeks to provide a structured library of code, maintain a system for distributing code and for managing code packages, and promote a standard coding style.PEAR is broken into three classes: PEAR Core Components, PEAR Packages, and PECL Packages. The Core Components include the base classes of PEAR and PEAR_Error, along with database, HTTP, logging, and e-mailing functions. The PEAR Packages include functionality providing for authentication, networking, and file system features, as well as tools for working with XML and HTML templates.

Distinguish between urlencode and urldecode?
This method is best when encode a string to used in a query part of a url. it returns a string in which all non-alphanumeric characters except -_. have replece with a percentege(%) sign . the urldecode->Decodes url to encode string as any %and other symbole are decode by the use of the urldecode() function.

What are the different errors in PHP?
In PHP, there are three types of runtime errors, they are:

Warnings:
These are important errors. Example: When we try to include () file which is not available. These errors are showed to the user by default but they will not result in ending the script.
Notices:
These errors are non-critical and trivial errors that come across while executing the script in PHP. Example: trying to gain access the variable which is not defined. These errors are not showed to the users by default even if the default behavior is changed.
Fatal errors:
These are critical errors. Example: instantiating an object of a class which does not exist or a non-existent function is called. These errors results in termination of the script immediately and default behavior of PHP is shown to them when they take place. Twelve different error types are used to represent these variations internally.

What is a REST API?
An API is an interface which can be a program or a web application which is capable to communicate to other websites or programs

REST stands for REpresentational State Transfer and is an architectural style for exposing your program using existing protocols, typically HTTP

A REST API utilize HTTP Methods like GET/POST/DELETE/UPDATE etc to get or set data in a server

Give me the list of function you are usually using when you debug your PHP scripts ?
During the development time, i will put error_reporting(E_ALL); ini_set('display_errors', 1); on the top of the php script to display all the errors and notices.

I will use print_r, var_dump functions to debug logical errors, there are so many other function also available for the same.

What are magic constants in PHP?
Magic constants are predefined constants which starts and ends with double underscore (__).

Following are some of the magic constants.

__LINE__
__FUNCTION__
__CLASS__
__FILE__
__METHOD__
Does PHP support multiple inheritance ?
PHP does not support multiple inheritance it will support only single inheritance. We can use the keyword extent a class from another class

What is the use of print_r function?
print_r function can be used to display human readable format of an array

What happened if we pass '0' as the parameter to set_time_limit() function ?
It will set the the execution time as infinite

How to store the content of a file in to a a string variable?
File get contents function can be e used to to read the content of a file and save the the data into a variable

How to find the number of rows returned from a MySQL result set?
mysqli_num_rows function can be used to find the number of rows of a rasult set

What is the difference between the empty() and isset() ?
isset() function is used to check available is already declared or not while empty() function is used to check weather the variable has a value or not

What is the use of the key word global ?
If we declare a variable as 'global' then we can access it within the PHP functions

How to get the current memory usage in PHP?
memory_get_usage function can be used to get the memory usage information

What is scalar type declarations in in PHP 7?
It's a new feature in PHP 7 we can declare scalar types like inch string bullion fraught

Explain anonymous classes in PHP 7?
Anonymous classes does not require any name this anonymous classes can be e defined using the new class. It will internal generate class names so we don't have to to give names to the classes. IT can replace ful class definition.

How to collect  IP address from an HTTP request ? 
$_SERVER['REMOTE_ADDR'];

How to collect  IP address of the Web server in php ? 
$_SERVER['SERVER_ADDR'];

How to enable error reporting ?
error_reporting(E_ALL);
What is $_GLOBAL ?
It is an associative array which containing references to all variables currently defined in the global scope of the script.

What is .htaccess file ?
.htaccess is a configuration file used to alter the default behavior of a Apache web server software. Most common usage is to redirect the http request to some URLs based on some conditions. For example, we can hide the .html or .php extensions of the URLs to make it SEO friendly
How to print structured information about a available in PHP ?
var_dump — This function displays structured information about one or more expressions that includes its value and type. Objects and arrays are explored recursively with values indented to show structure.

Usage   var_dump($a);

What is the difference between var_dump and print_r ?
var_dump will display all the information of a variable including keys values and types while print_r display the keys and values only in a human readable format.

What is automatic type conversion ?
In php we can declare variables without specifying its type, php it do that process automatically since PHP is a loosely types language.

For example : 

<?php
//$count is a string variable
$count = "5";
//$count is an int variable
$count = "5";
How to make API calls from php scripts ?
We can use cURL library to make HTTP calls from a php script

<?php

$ch = curl_init();
$postData = 'var1=value1&var2=value2&var3=value3';
curl_setopt($ch, CURLOPT_URL, "http://mydomain.com/ajaxurl";);
curl_setopt($ch, CURLOPT_POST, 1 );
curl_setopt($ch, CURLOPT_POSTFIELDS, $postData );
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true );
$ch = curl_exec($ch);
$ch = curl_close($ch);
echo $result;die;
How to change the php configurations at run time ?
We can use `ini_set` function to change the configurations of php at run time.

How can we resolve the errors like 'Maximum execution time of 30 seconds exceeded' ?
We can use the following code to increase the maximum execution time of the script 

ini_set('max_execution_time', 300);
We can also set the max_execution_time for all the scripts in a website by the following code in .htaccess file

<IfModule mod_php5.c>  php_value max_execution_time 300  </IfModule> 
But, we must try to optimize the php script to avoid this kind of situations as a part good user experience.

How to avoid email sent through php getting into spam folder?
There's no special method of keeping your emails from being identified as spam. However we can consider some points that cause this problem. Let me explain few common reasons.

1. sending mail using the `mail` function with minimum parameters

    We must use all possible mail headers like `MIME-version`, `Content-type`, `reply address`, `from address` etc in order to avoid this situation

2. Not using a proper SMTP mail script like PHPmailer or SwiftMailer with an actual e-mail credentials including username, password etc

    If we are able to send e-mail from an actual e-mail account using an SMTP mailer script with username and password, then we can avoid  

If you’re on a shared web server, consider buying a unique IP address for yourself, because others using your IP may have gotten your IP blacklisted for spam. Do not send more than 250 emails to each provider per hour.

Give your users unsubscribe link and view in browser link, if they cannot see the email properly they will mark you as spam, if they no longer want emails for you they will mark you as spam. 

How can we prevent SQL injection in PHP?

Most popular way is, use prepared statements and parameterized queries. These are SQL statements that are sent to and parsed by the database server separately from any parameters. This way it is impossible for an attacker to inject malicious SQL.

You basically have two options to achieve this:

Using PDO (for any supported database driver):

$stmt = $pdo->prepare('SELECT * FROM employees WHERE name = :name');
$stmt->execute(array('name' => $name));
foreach ($stmt as $row) {
      // do something with $row  
}
Using MySQLi (for MySQL):

$stmt = $dbConnection->prepare('SELECT * FROM employees WHERE name = ?');  
$stmt->bind_param('s', $name);
$stmt->execute();
$result = $stmt->get_result();
while ($row = $result->fetch_assoc()) {
      // do something with $row  
}
If you're connecting to a database other than MySQL, there is a driver-specific second option that you can refer to (e.g. pg_prepare() and pg_execute() for PostgreSQL). PDO is the universal option.
How to fix “Headers already sent” error in PHP ?
No output before sending headers. there should not be any output (i.e. echo.. or HTML codes) before the header(.......);command. remove any white-space(or newline) before <?php and after ?> tags. After header(...); you must use exit;

How to return JSON from a PHP Script ?
We have to set the Content-Type header with application/json  as the value and print a valid JSON data using echo method

For example

<?php  
 $data = /** whatever you're serializing **/;  
 header('Content-Type: application/json');  
 echo json_encode($data);
How can we fix "Memory size Exhausted" errors ?
You can fix it at run time or can be set required size on the php.ini file

ini_set('memory_limit', '512M'); // In a php script at run time
When to use self over $this?
Use $this to refer to the current object. Use self to refer to the current class. In other words, use $this->member for non-static members, use self::$member for static members.

How to redirect the user to one page to another using php ?
we have a special php function called header, can be used to do the same header("Location: new-page.php");. We already defined the step for the same in our blog post How to php redirect

What is CSS?
CSS Stands for Cascading Style Sheets. It is a platform independent web page designing language and it will saves time because we can write this once and use the same in other pages.

What are the ways to integrate css in a web page
There are three ways to integrate css in a web page

Inline : It is used to Apply some styles to an element including its child elements using style attribute
Embedded : We can write group of styles with in the html <style></style> tag
Linked/ Imported : We can specify an external stylesheet url using the following code <link rel="stylesheet" type="text/css" href="custom.css" />
Listout some widely using CSS Measurement Units
px - Defines a measurement in screen pixels.
% - Defines a measurement as a percentage relative to another value, mainly an enclosing element.
em - It is a relative measurement for the height of a font used in em spaces in a web page. Because 1em unit is equivalent to the size of a given font, if you assign a font to 10pt, each "em" unit would be 10pt; thus, 2em would be 20pt.
vh - 1% of viewport height, Viewport measurements are very useful when developing a responsive web page or Hybrid App.
vw - 1% of viewport height.
vw - 1% of viewport height.
Which property allows you to control the shape or appearance of the marker of a list?
The list-style-type allows you to control the shape or appearance of the marker.

Which property specifies whether a long point that wraps to a second line should align with the first line or start underneath the start of the marker of a list?
The list-style-position specifies whether a long point that wraps to a second line should align with the first line or start underneath the start of the marker.

Which property specifies an image rather than a bullet point or number for the marker of a list?
The list-style-image specifies an image for the marker rather than a bullet point or number.

Which property serves as shorthand for the styling properties of a list?
The list-style serves as shorthand for the styling properties.

Which property specifies the distance between a marker and the text in the list?
The marker-offset specifies the distance between a marker and the text in the list.

Which property specifies the bottom padding of an element?
The padding-bottom specifies the bottom padding of an element.

Which property specifies the top padding of an element?
The padding-top specifies the top padding of an element.

Which property specifies the left padding of an element?
The padding-left specifies the left padding of an element.

Which property specifies the right padding of an element?
The padding-right specifies the right padding of an element.

Which property serves as shorthand for the all the padding properties of an element?
The padding serves as shorthand for the all the padding properties.

Which property allows you to specify the type of cursor that should be displayed to the user?
The cursor property of CSS allows you to specify the type of cursor that should be displayed to the user.

Which value of cursor property changes the cursor based on context area it is over?
auto − Shape of the cursor depends on the context area it is over. For example, an 'I' over text, a 'hand' over a link, and so on.

Which property is used to set all the outlining properties in a single statement?
The outline property is used to set all the outlining properties in a single statement.

Which property is used to set the height of a box?
The height property is used to set the height of a box.

Which property is used to set the width of a box?
The width property is used to set the width of a box.

Why is @import only at the top?
@import is preferred only at the top, to avoid any overriding rules. Generally, ranking order is followed in most programming languages such as Java, Modula, etc. In C, the # is a prominent example of a @import being at the top.

What is contextual selector?
Selector used to select special occurrences of an element is called contextual selector. A space separates the individual selectors. Only the last element of the pattern is addressed in this kind of selector. For e.g.: TD P TEXT {color: blue}

How html5 is different from html4?
HTML5 is an upgraded version of html4.01 and introduced some new features such as Audio, Video, Canvas, Drag & Drop, Storage, Geo Location, Web Socket etc and also introduced some new html tags such as article, section, header, aside and nav etc which help to create the page layout faster. HTML 5 will handle the inaccurate syntax of the tags and it simplified the doctype and character set declaration. It also deprecated some html tags like center, font, strike, acronym, applet etc.

How browsers detect the html version of a webpage?
We must declare the doctype at the top of the page, it is an instruction to the web browser about what version of HTML the page is written in.

Write down the Doctype declaration of html5 and html4
html5
<!DOCTYPE html> 
html4
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
What are the new form attributes in HTML5 ?
Placeholder, novalidate, autocomplete, required , autofocus, pattern, list, multiple, formnovalidate etc

What are the different units for expressing a length in css?
rem, vh, vw, ex, ch, em, %, px, in, cm, mm, pt and pc

Unit	Description
em	1 em is the computed value of the font-size on the element on which it is used.
ex	1 ex is the current font’s x-height. The x-height is usually (but not always, e.g., if there is no ‘x’ in the font) equal to the height of a lowercase ‘x’
ch	1 ch is the advance of the ‘0’ (zero) glyph in the current font. ‘ch’ stands for character.
rem	1 rem is the computed value of the font-size property for the document’s root element.
vw	1vw is 1% of the width of the viewport. ‘vw’ stands for ‘viewport width’.
vh	1vh is 1% of the height of the viewport. ‘vh’ stands for ‘viewport height’.
vmin	Equal to the smaller of ‘vw’ or ‘vh’
vmax	Equal to the larger of ‘vw’ or ‘vh’
What is SVG?
SVG stands for Scalable Vector Graphics, It is an XML based two-dimensional vector graphics image format.


What is character encoding in HTML ?
Character encoding is a rule for how to interpret raw zeroes and ones into real characters. There are two main character encoding representations used in html documnets such as UTF-8, and ISO-8859-1. The default character set for HTML5 is UTF-8. The following syntax is used to set the character encoding in an html document <meta charset="UTF-8">

What is HTML Entities ?
HTML Entities are some special words which is used to replace the reserved characters or some other characters that are not present on your keyboard can also be replaced by entities in your HTML, For example if you need to display < ( 'Less than' symbol ) In your html document, You can use &lt; Entity

What is mean by Responsive Web Site ?
It will looks good in all screen resolutions device type. We can utilize css media quries to re-arrange the with of an element also we can hide or display any elements in a web page. Bootstrap is a widely using css framework to make responsive web pages quikly

List out some HTML5 tags
header, footer, main, nav, section, article, aside etc..

What is the use of HTML5 Canvas element ?
It is used to draw graphics on a web page by the help of javascript.

What is the use of 'placeholder' attribute in HTML5?
It is used to display some text with in a textbox or textarea and the text will disappear when user start typing in that box



1. ### What are the pros of using Laravel?

There are 25 reasons why to choose Laravel. While other frameworks also offer MVC, Laravel goes far ahead and offers,
1. Eloquent
2. Query Builder
3. Mail
4. API Resources
5. 3rd Party Packages
6. Bindings
7. Service Container
8. Service Provider
9. Broadcasting
10. Routes
11. Single page application features
12. Jobs and Queues
13. Tasks and Task scheduling
14. Events and Notifications
15. Artisan
16. Migration and Seeders
17. Sessions
18. Log
19. Caching
20. Collections
21. Request
22. Cookies
23. File system and multi file systems
24. Databases and multi databases
25. Lumen


    
2. ### What is inheritance in PHP?

When a class inherits another class. It uses extends.
 ```
 <!DOCTYPE html>
 <html>
 <body>

 <?php
 class Fruit {
   public $name;
   public $color;
   public function __construct($name, $color) {
     $this->name = $name;
     $this->color = $color; 
   }
   public function intro() {
     echo "The fruit is {$this->name} and the color is {$this->color}."; 
   }
 }

 // Strawberry is inherited from Fruit
 class Strawberry extends Fruit {
   public function message() {
     echo "Am I a fruit or a berry? "; 
   }
 }

 $strawberry = new Strawberry("Strawberry", "red");
 $strawberry->message();
 $strawberry->intro();
 ?>

 </body>
 </html>
 ```
  **[⬆ Back to Top](#table-of-contents)**
    
3. ### What is dependency manager?

   It is a package manager which manages 3rd party libraries for us.
   
  **[⬆ Back to Top](#table-of-contents)**
    
4. ### What is api php?

    The place where we write API route for mobile and API usage. Like http://localhost:8080/api/test
    ```
    Route::get('/test', function () {
        $path = storage_path() . "/app/json/options/docs.json";
        return view('skin/dev-wireframe', array('menu' => json_decode(file_get_contents($path), true)));
    });
    ```
     **[⬆ Back to Top](#table-of-contents)**
     
5. ### What is Method Overriding?

    Method performs diffrent on different inputs (arguments.)

 **[⬆ Back to Top](#table-of-contents)**

6. ### What is overloading?

    Inherited class reimplements the function/method.
    
    Note: PHP doesn't support overloading.
    ```
    <?php

    class Foo {
       function myFoo() {
          return "Foo";
       }
    }

    class Bar extends Foo {
       function myFoo() {
          return "Bar";
       }
    }

    $foo = new Foo;
    $bar = new Bar;
    echo($foo->myFoo()); //"Foo"
    echo($bar->myFoo()); //"Bar"
    ?>
   ```
  **[⬆ Back to Top](#table-of-contents)**
   
    
7. ### What are Abstract classes?

    It has function declarations but not definitions. Child classes implement the classes according to their needs. Created using abstract keyword.

    ```
   <?php
   abstract class ParentClass {
     abstract public function someMethod1();
     abstract public function someMethod2($name, $color);
     abstract public function someMethod3() : string;
   }
   ?>
    ```


   **[⬆ Back to Top](#table-of-contents)**
    
8. ### What are Views?

  Views is the fornt end of Laravel. Stored in `resources/views`.

    ```
    <html>
        <body>
            <h1>Hello, {{ $name }}</h1>
        </body>
    </html>
    ```


   **[⬆ Back to Top](#table-of-contents)**
    
9. ### 	What are Interfaces?
    A class with only function declaration and not definition.
    
    The difference between Abstract class and interface? Abstract class may have definition that child classes can change but interface is always only declaration and no definition.
    

   **[⬆ Back to Top](#table-of-contents)**
    
10. ### What are access modifiers?

    There are three access modifiers:

    public - the property or method can be accessed from everywhere. This is default
    protected - the property or method can be accessed within the class and by classes derived from that class
    private - the property or method can ONLY be accessed within the class


   **[⬆ Back to Top](#table-of-contents)**
    
11. ### What is OOP parent child relationship?
  Parent is the class from which we inherit and the class that inherits from other is called child class. The relationship between them is called parent/child relationship. In PHP a class can only have one parent. Other languages like Java allow multiple inheritance.

   **[⬆ Back to Top](#table-of-contents)**
    
12. ### When are Magic methods?

    Predefined methods which start with double underscores i.e __function_name().
    
   **[⬆ Back to Top](#table-of-contents)**
    
13. ### What are traits?

   To solve the problem of multiple inheritance i.e one class inheriting from two classes, we use traits which provides us similar functionality.

   **[⬆ Back to Top](#table-of-contents)**
    
14. ### What are php globals?

    Globals i.e global variables are accessible everywhere. These are,
    $GLOBALS
    $_SERVER
    $_REQUEST
    $_POST
    $_GET
    $_FILES
    $_ENV
    $_COOKIE
    $_SESSION


   **[⬆ Back to Top](#table-of-contents)**
    
15. ### Talk about REST

  REST is the most widely used API implementation method. Other popular ones include SOAP. Rest uses JSON. Its easy to implement.

   **[⬆ Back to Top](#table-of-contents)**
    
16. ### How will you increase security in a Contact form using PHP?

   A. USE CSRF, JWT token.
   B. Check the input for SQL injections before inserting the data into database.

   **[⬆ Back to Top](#table-of-contents)**
    
17. ### What are Facades?

    Facades are used to hide implementation details and complexities from end user making him/her feel like interacting with a black box.

   **[⬆ Back to Top](#table-of-contents)**
    
18. ### What is Repository Pattern?

    Repository pattern is used to create templates where implementation details are left to be implemented in child classes. It helps with further expansion of code and avoid bottlenecks in class updation.

   **[⬆ Back to Top](#table-of-contents)**
    
19. ### What is Authentication using Passport?
    
    Passport provides a better way to create API.

   **[⬆ Back to Top](#table-of-contents)**
    
20. ### What Unit testing?
    Testing every function

   **[⬆ Back to Top](#table-of-contents)**
    
21. ### What is Caching?

    Configured using `config/cache.php`. Used for database caching. Popular ways Redis and Memcache.

   **[⬆ Back to Top](#table-of-contents)**
    
22. ### What is Unit Testing?

    Writing a test for every unit (function or class) you write.

   **[⬆ Back to Top](#table-of-contents)**
   
23. ### How to setup Emails?

    Using PHP's `mail()` function amnd Laravel's `sendmail()` function. You can custoimize it using templates.

  **[⬆ Back to Top](#table-of-contents)**
  
  
24. ### What are Queues?

    Queue is a line of jobs to be proccessed. You can create multiple queues which is multiple lines of jobs
    
   **[⬆ Back to Top](#table-of-contents)**
    
25. ### What are Jobs?

    Job is a task being performed in the background.

   **[⬆ Back to Top](#table-of-contents)**
   
   
26. ### How to setup Emails?

   Use Laravel's sendmail() function and create a mail template.

   **[⬆ Back to Top](#table-of-contents)**
    
27. ### one ring bells at 20 sec, second will 40 sec and third will 60.at what time these three will ring together?

    2 minutes.

   **[⬆ Back to Top](#table-of-contents)**
    
28. ### Get the last thee max salaried person from table via sql.?
```
SELECT TOP 3 names
FROM employees
ORDER BY SALARY DESC
```

   **[⬆ Back to Top](#table-of-contents)**
    
29. ### What is multithreading?

  Parallel executions of more than one threads. A thread is the smallest unit of a task.

   **[⬆ Back to Top](#table-of-contents)**
    
30. ### Does PHP support multithreading?

   Yes. Using pthreads.
   https://stackoverflow.com/questions/70855/how-can-one-use-multi-threading-in-php-applications

   **[⬆ Back to Top](#table-of-contents)**
    
   Write the code of upload a file in php?
```
<?php
if ($_SERVER['REQUEST_METHOD'] === 'POST') {
    $targetDir = 'uploads/'; // Directory where you want to store the uploaded files
    $targetFile = $targetDir . basename($_FILES['file']['name']); // Full path of the target file

    // Check if the file was uploaded without errors
    if (move_uploaded_file($_FILES['file']['tmp_name'], $targetFile)) {
        echo 'File uploaded successfully.';
    } else {
        echo 'There was an error uploading the file.';
    }
}
?>

<!-- HTML form for uploading a file -->
<!DOCTYPE html>
<html>
<body>
    <form action="" method="POST" enctype="multipart/form-data">
        <input type="file" name="file">
        <input type="submit" value="Upload">
    </form>
</body>
</html>

```
What is indexing?


