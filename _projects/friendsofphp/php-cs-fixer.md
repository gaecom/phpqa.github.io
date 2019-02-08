---
layout:             'project'
title:              'PHP Coding Standards Fixer 2'
order:              'php coding standards fixer 2'
tags:               ['code fixer', 'coding standards', 'psr', 'cli'] 

authors:            [{name: 'Fabien Potencier'}, {name: 'Dariusz Rumiński'}]

website:            [{url: 'http://cs.sensiolabs.org/'}]
license:            [{url: 'https://github.com/FriendsOfPHP/PHP-CS-Fixer/blob/master/LICENSE', label: 'MIT License'}]

github:             [{name: 'FriendsOfPHP/PHP-CS-Fixer'}]
packagist:          [{name: 'friendsofphp/php-cs-fixer'}]               
dockerhub:          [{name: 'phpqa/php-cs-fixer'}]     

dependencies:       []
brew:               {name: 'homebrew/php/php-cs-fixer'}
composer-global:    {command: 'php-cs-fixer'}
phar:               {url: {'No HTTPS': 'http://cs.sensiolabs.org/download/php-cs-fixer-v2.phar'}}

---

The [{{ page.title }}]({{ page.url | absolute_url }}) tool fixes most issues in your code when you want to follow the PHP coding standards as defined in the PSR-1 and PSR-2 documents and many more.

<!--more--> 

If you are already using a linter to identify coding standards problems in your code, you know that fixing them by hand is tedious, especially on large projects. This tool does not only detect them, but also fixes them for you.
