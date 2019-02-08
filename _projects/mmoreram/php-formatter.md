---
layout:             'project'
title:              'PHP Formatter'
order:              'php formatter'
tags:               ['coding standards', 'cli'] 

authors:            [{name: 'Marc Morera'}] 

website:            [{url: 'https://github.com/mmoreram/php-formatter'}]
license:            [{url: 'https://github.com/mmoreram/php-formatter/blob/master/LICENSE', label: 'MIT License'}]

github:             [{name: 'mmoreram/php-formatter'}]
packagist:          [{name: 'mmoreram/php-formatter'}]               
dockerhub:          [{name: 'phpqa/php-formatter'}]     

dependencies:       []
composer-global:    {version: 'dev-master', command: 'php-formatter'}
phar:               {url: {'master': 'https://github.com/mmoreram/php-formatter/blob/master/build/php-formatter.phar?raw=true'}}

---

[{{ page.title }}]({{ page.url | absolute_url }}) aims to provide you some bulk actions for your PHP projects to ensure their consistency.

<!--more-->

None of them fixes PSR rules.
