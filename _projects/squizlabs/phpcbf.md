---
layout:             'project'
title:              'PHP Code Beautifier and Fixer'
order:              'php code beautifier and fixer'
tags:               ['coding standards', 'code fixer', 'code beautifier', 'cli'] 

authors:            [{name: 'Greg Sherwood'}] 

website:            [{url: 'https://pear.php.net/package/PHP_CodeSniffer'}]
license:            [{url: 'https://github.com/squizlabs/PHP_CodeSniffer/blob/master/licence.txt', label: 'BSD 3-clause "New" or "Revised" License'}]

github:             [{name: 'squizlabs/PHP_CodeSniffer'}]
packagist:          [{name: 'squizlabs/php_codesniffer'}]               
dockerhub:          [{name: 'phpqa/phpcbf'}]     

dependencies:       []
composer-dev:       {command: 'vendor/bin/phpcbf'}
composer-global:    {command: 'phpcbf'}
git:                {command: 'bin/phpcbf'}
phar:               {url: 'https://squizlabs.github.io/PHP_CodeSniffer/phpcbf.phar'}

---

[{{ page.title }}]({{ page.url | absolute_url }}) fixes violations of a defined coding standard.

<!--more-->

PHP Code Beautifier and Fixer is part of a set of two PHP scripts; the main phpcs script that tokenizes PHP, JavaScript and CSS files
to detect violations of a defined coding standard, and a second phpcbf script to automatically correct coding standard violations.
PHP_CodeSniffer is an essential development tool that ensures your code remains clean and consistent.

