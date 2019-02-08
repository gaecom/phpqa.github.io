---
layout:             'project'
title:              'PHP Copy/Paste Detector'
order:              'php copy/paste detector'
tags:               ['bugs finder', 'dry', 'code duplication', 'cli'] 

authors:            [{name: 'Sebastian Bergmann'}]

website:            [{url: 'https://github.com/sebastianbergmann/phpcpd'}]
license:            [{url: 'https://github.com/sebastianbergmann/phpcpd/blob/master/LICENSE', label: 'BSD 3-clause "New" or "Revised" License'}]

github:             [{name: 'sebastianbergmann/phpcpd'}]
packagist:          [{name: 'sebastian/phpcpd'}]               
dockerhub:          [{name: 'phpqa/phpcpd'}]     

dependencies:       []
composer-dev:       {command: 'vendor/bin/phpcpd'}
phar:               {url: 'https://phar.phpunit.de/phpcpd.phar'}

---

[{{ page.title }}]({{ page.url | absolute_url }}) is a Copy/Paste Detector for PHP code.

<!--more--> 

It scans a PHP project for [duplicated code](http://en.wikipedia.org/wiki/Duplicate_code), in order to "Don't Repeat Yourself" (DRY).
