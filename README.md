# Nexed Kanban
A Basic Kanban App for NexEd Long-Term Planning

For Bit Academy students, especially those in their first year, creating a long-term plan can be challenging. This app offers a simple Kanban system to help students organize and plan for long-term goals, such as achieving their VSA or BSA.

The project is designed with a structure that encourages (first-year) students to actively contribute to its development.

## Software

- [PHP ^8.3](https://www.php.net/archive/2024.php#2024-09-26-1)
- [SlimFramework](https://www.slimframework.com/)
- [Petite Vue](https://github.com/vuejs/petite-vue)
- [SQLite](https://www.sqlite.org/)
- [Vanilla Javascript](https://developer.mozilla.org/) (No extra modules)

> **NOTE:**
> 
> In this project the term Vanilla JavaScript is referred to JavaScript code that is written without the aid of any external libraries or frameworks other than Petite Vue. 
 
## Features
- Each user gets his own Dataset in the form of a SqlLite Database
- Set the long term goal
- Add the modules to your goal
- Auto generation of tasks based on the modules in your goal
- Auto generation of the kanban bord.


# Slim Framework 4 Skeleton Application

[![Coverage Status](https://coveralls.io/repos/github/slimphp/Slim-Skeleton/badge.svg?branch=master)](https://coveralls.io/github/slimphp/Slim-Skeleton?branch=master)

The applicatyion is based on skeleton Slim Framework 4 application. This application uses the latest Slim 4 with Slim PSR-7 implementation and PHP-DI container implementation. It also uses the Monolog logger.

* Point your virtual host document root to your new application's `public/` directory.
* Ensure `logs/` is web writable.

To run the application in development, you can run these commands 

```bash
cd [my-app-name]
composer start
```

Or you can use `docker-compose` to run the app with `docker`, so you can run these commands:
```bash
cd [my-app-name]
docker-compose up -d
```
After that, open `http://localhost:8080` in your browser.

Run this command in the application directory to run the test suite

```bash
composer test
```


