---
layout:             'project'
title:              'Qafoo Quality Analyzer'
order:              'qafoo quality analyzer'
tags:               ['metrics', 'cli']

authors:            [{name: 'Kore Nordmann'}]

website:            [{url: 'https://github.com/Qafoo/QualityAnalyzer'}]
license:            [{url: 'https://github.com/Qafoo/QualityAnalyzer/blob/master/LICENSE', label: 'GNU Affero General Public License v3.0'}]

github:             [{name: 'Qafoo/QualityAnalyzer'}]
packagist:          [{name: 'qafoo/quality-analyzer'}]               
dockerhub:          [{name: 'phpqa/analyze'}] 

dependencies:       ['ext-zip', 'git']
git:                {install-composer-dependencies: true, command: 'bin/analyze'}

---

[{{ page.title }}]({{ page.url | absolute_url }}) is a tool to visualize metrics and source code.

<!--more--> 
