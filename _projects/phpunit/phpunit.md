---
layout:             'project'
title:              'PHPUnit'
order:              'phpunit'
tags:               ['testing', 'cli'] 

authors:            [{name: 'Sebastian Bergmann'}] 

website:            [{url: 'http://www.phpunit.de/'}]
license:            [{url: 'https://github.com/sebastianbergmann/phpunit/blob/master/LICENSE', label: 'BSD 3-clause "New" or "Revised" License'}]

github:             [{name: 'sebastianbergmann/phpunit'}]
packagist:          [{name: 'phpunit/phpunit'}]               
dockerhub:          [{name: 'phpqa/phpunit'}]     

dependencies:       []
composer-dev:       {command: 'vendor/bin/phpunit'}
phar:               {url: 'https://phar.phpunit.de/phpunit.phar'}

---

[{{ page.title }}]({{ page.url | absolute_url }}) is a programmer-oriented testing framework for PHP.
 
<!--more--> 

It provides both a framework that makes the writing of tests easy
as well as the functionality to easily run the tests and analyse their results.

It is an instance of the xUnit architecture for unit testing frameworks.
