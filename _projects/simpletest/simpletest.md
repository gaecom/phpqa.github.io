---
layout:             'project'
title:              'SimpleTest'
order:              'simpletest'
tags:               ['testing']

authors:            [{name: 'Marcus Baker'}, {name: 'Jason Sweat'}, {name: 'Travis Swicegood'}, {name: 'Perrick Penet'}, {name: 'Edward Z. Yang'}, {name: 'Jens A. Koch'}]

website:            [{url: 'http://simpletest.org/'}] 
license:            [{url: 'https://github.com/simpletest/simpletest/blob/master/LICENSE', label: 'LGPL-2.1'}] 

github:             [{name: 'simpletest/simpletest'}] 
packagist:          [{name: 'simpletest/simpletest'}]
composer-dev:       {command: 'vendor/bin/simpletest'}

---

[{{ page.title }}]({{ page.url | absolute_url }}) is a framework for unit testing, web site testing and mock objects for PHP.

<!--more--> 

Users of [JUnit](http://www.junit.org/) will be familiar with most of the interface.
The [JWebUnit](http://jwebunit.sourceforge.net/) style functionality is more complete now.
It has support for SSL, forms, frames, proxies and basic authentication.
The idea is that common but fiddly PHP tasks, such as logging into a site, can be tested easily.
