
# PHP-Interview-Questions

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







If i know what is ACID?
different raid systems
If a parent record was accidentally deleted without removing the child records, what query could you use to determine what records were "orphaned".
list Background Processes in oracle Database
Regarding Replication, deadlock, installation, upgradation

Q. What is PHP?
Q. Is PHP case sensitive?
Q. Is PHP weakly typed language?
Q. How do we install PHP?
Q. What is Composer?
Q. How to check current PHP version and other information about our system?
Q. What is interpreter?
Q. Is PHP compiled or interpreted?
Q. Explain datatypes in PHP?
Q. What are rules for naming a variable?
Q. How will you define a constant?
Q. What is the purpose of constant() function?
Q. What are the differences between constants and variables?
Q. What are the different scopes of variables?
Q. What is string?
Q. What is the difference between single quoted string and double quoted string?
Q. How can you convert string into array elements?
Q. How can you convert array into strings?
Q. How can you concatenate two or more strings?
Q. Differentiate between echo and print()?
Q. Explain static variables?
Q. What are PHP magic constants?
Q. Why do we need trim() function?
Q. Can you count the number of words in a string?
Q. How to reverse a string?
Q. How to find the position of a specific text in a string?
Q. How can you change cases in a string?
Q. Can you replace a substring?
Q. Differentiate between str_replace() and str_ireplace()?
Q. Differentiate between printf() and print()?
Q. Differentiate between strstr() & strchr() functions?
Q. Differentiate between strstr() and stristr()?
Q. Can you encode a string in PHP?
Q. Differentiate between strcmp() and strncmp()?
Q. Is it possible to remove the HTML tags from data?
Q. What is the use of gettype() in PHP?
Q. What is heredoc and nowdoc?
Q. Explain if-else statement?
Q. Explain switch statement with example?
Q. Differentiate between switch and if-else statement?
Q. What are the different types of operators?
Q. Explain arithmetic operators?
Q. Explain the assignment operators?
Q. Explain the logical operators?
Q. Explain the unary operators?
Q. Explain the comparison operators?
Q. Differentiate between === and == operators in PHP?
Q. Explain pre and post increment with example?
Q. What do you mean by operator overloading?
Q. How many loops are available in PHP?
Q. Explain while loop with example?
Q. Explain do-while loop with example?
Q. Explain for loop with example?
Q. Explain foreach loop with example?
Q. How can you implement an infinite loop in PHP?
Q. How can you implement recursion in PHP?
Q. Explain break statement with example?
Q. Explain continue statement with example?
Q. Give example of declaration in php?
Q. What is require in PHP?
Q. What is an array?
Q. How can you print an array in PHP?
Q. What do we mean by the base address of an array?
Q. What do we mean by keys and values?
Q. What are the keys & values in an indexed array?
Q. How can we convert array into string?
Q. How can we convert a string into an array elements?
Q. How can we concatenate arrays in PHP?
Q. Which function counts all the values of an array?
Q. How can we check if an element exists in an array?
Q. Which function inserts an element to the end of an array?
Q. What is the use of array_chunk() function?
Q. Why do we use extract()?
Q. What is a function?
Q. What are the different types of functions?
Q. Classify function on basis of parameters?
Q. Differentiate between parameterized and non parameterized functions?
Q. Does PHP support both call by value and call by reference?
Q. Explain call by value?
Q. Explain call by reference?
Q. What are the function declaration rules?
Q. How can we declare user defined functions?
Q. What do we mean by actual and formal parameters?
Q. Maximum how many arguments are allowed in a function in PHP?
Q. Explain header()?
Q. What do we mean by return type of a function?
Q. What is the return type of a function that doesn't return anything?
Q. Do we need to mention the return type of a function explicitly in PHP?
Q. What is function that can be used to build a function that accepts any number of arguments?
Q. Explain the return statement?
Q. Can we use multiple return statements in a function?
Q. What is the use of ini_set()?
Q. What is the difference between unlink and unset functions?
Q. How ereg() function works?
Q. How eregi() function works?
Q. What is the purpose of getdate() function?
Q. What is the purpose of date() function?
Q. How will you call member functions of a class?
Q. How can we display the correct URL of the current webpage?
Q. How to get the information about the uploaded file in the receiving script?
Q. What do we mean by server?
Q. What are PHP superglobals?
Q. How will we get information sent via GET method?
Q. How will you get information sent via POST method?
Q. What is the purpse $_REQUEST variable?
Q. What is the purpose of $_FILES variable?
Q. What is the purpose of $GLOBALS variable in PHP?
Q. What is the purpose of $_SERVER variable in PHP?
Q. What is the purpose of $_COOKIE variable in PHP?
Q. What do you mean by environment variable in PHP?
Q. What is the purpose of $_ENV variable in PHP?
Q. What is the purpose of $_SESSION variable in PHP?
Q. How will you redirect a page?
Q. What is the purpose $_PHP_SELF variable?
Q. How will you get the browser details using PHP?
Q. What do you mean by HTTP status codes?
Q. What are the HTTP client error codes?
Q. What are the informational status codes?
Q. What are the HTTP success codes?
Q. How do you get the redirection related information?
Q. What is API?
Q. What is REST API?
Q. What is JSON?
Q. Why do we need JSON?
Q. How can you exchange data using JSON?
Q. Differentiate between JSON & XML?
Q. What are the advantages of JSON?
Q. What is Session?
Q. What is Cookie?
Q. Differentiate between Session & Cookie?
Q. How do we start a session?
Q. How can we set session variable?
Q. How to remove value from session variable?
Q. When do we need to set session variables?
Q. When do we need a session and not a cookie?
Q. When do we need a cookie and not a session?
Q. How can we set a cookie?
Q. How to modify a cookie value?
Q. How will we make a check that a cookie is set or not?
Q. How to retrieve all cookie values?
Q. How to delete a cookie?
Q. How can we implement 'remember me' using PHP?
Q. Classify cookies?
Q. How will you delete a cookie?
Q. How to track login and logout using PHP?
Q. How to create a file?
Q. What are the other way to write in a file?
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







1. ### What are the pros of using Laravel?

 A. Most demanded PHP framework.
 B. Great documentation.
 C. MVC based.
 D. ORM for DB.
 E. Blade templating engine


 **[⬆ Back to Top](#table-of-contents)**
    
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

   

   **[⬆ Back to Top](#table-of-contents)**
    
29. ### What is multithreading?

  Parallel executions of more than one threads. A thread is the smallest unit of a task.

   **[⬆ Back to Top](#table-of-contents)**
    
30. ### Does PHP support multithreading?

   Yes. Using pthreads.
   https://stackoverflow.com/questions/70855/how-can-one-use-multi-threading-in-php-applications

   **[⬆ Back to Top](#table-of-contents)**
    
    
