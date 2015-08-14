## Laravel 5.1 Angular Material Starter
> Version 2.7

<a href="https://infinite-dusk-3948.herokuapp.com/" target="_blank">View DEMO</a>

![Laravel & Angular](http://i.imgur.com/ZbLzOPP.jpg)


##### Table of Contents
[Overview](#overview)  
[Installation](#installation)  
[Issues, questions and feature requests](#issues)  
[Planned features](#planned_features)  

<a name="overview"></a>
## OVERVIEW
This is a starter project that gives you an out of the box configuration Laravel 5.1 and AngularJS (folder by feature architecture).
Here are the goodies that you'll get:

* Laravel 5.1
* Angular
* Angular Material
* Blazing fast Elixir 3.0 configuration with custom tasks
* artisan generators for angular (artisan ng:feature name, artisan ng:dialog name, etc..)
* check out the full <a href="https://infinite-dusk-3948.herokuapp.com/" target="_blank">list of features</a>


<a name="installation"></a>
## Installation

    composer create-project jadjoubran/laravel5-angular-material-starter --prefer-dist
    cd laravel5-angular-material-starter
    #fix database credentials in .env
    npm install -g gulp bower
    npm install
    bower install
    gulp && gulp watch
    php artisan serve
* You're ready to go! <a href="http://localhost:8000" target="_blank">http://localhost:8000</a>
* Star the repo and submit your feedback as a new issue or to <a href="https://twitter.com/joubranjad" target="_blank">@JoubranJad</a>

<a name="issues"></a>
## Issues, questions and feature requests
Open a new issue, I'd love to help.


<a name="planned_features"></a>
## Planned features


- New demo pages: Elixir, Rest API, loading bar, debugbar, filters, JWT
- Migrate to open source hosting
- make gulp --production part of the automated release
- jwt auth example (with seed) + route authentication
- composer.lock committed again (issue) - also issue with sourcemap files
- choose between JWT (disable CSRF) or not (enable CSRF)
- automate tests
- even better support for 5.1 (fork?)
