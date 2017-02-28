---
title: Introduction
---

**THIS PACKAGE AND IT'S DOCUMENTATION ARE STILL IN DEVELOPMENT**


We all dream of servers that need no maintenance at all. But unfortunately in reality this is not the case. Disks can get full, processes can crash, the server can run out of memory...

This package keeps an eye on the health of all your servers. There are a few [checks that come out of the box](https://docs.spatie.be/laravel-server-monitor/v1/monitoring-basics/built-in-checks). [Adding new checks](https://docs.spatie.be/laravel-server-monitor/v1/monitoring-basics/writing-your-own-checks) is a breeze.

When something goes wrong it can [notify you](https://docs.spatie.be/laravel-server-monitor/v1/monitoring-basics/notifications-and-events) via Slack or mail. Here's how a Slack notifications look like:

<img src="/images/server-monitor/check-failed.jpg" class="screenshot -slack">

Behind the scenes [Laravel's native notification system](https://laravel.com/docs/5.4/notifications) is leveraged so you can use one of the [many notification drivers](http://laravel-notification-channels.com/).

## We have badges!

<section class="article_badges">
    <a href="https://github.com/spatie/laravel-server-monitor/releases"><img src="https://img.shields.io/github/release/spatie/laravel-server-monitor.svg?style=flat-square" alt="Latest Version"></a>
    <a href="LICENSE.md"><img src="https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square" alt="Software License"></a>
    <a href="https://travis-ci.org/spatie/laravel-server-monitor"><img src="https://img.shields.io/travis/spatie/laravel-server-monitor/master.svg?style=flat-square" alt="Build Status"></a>
    <a href="https://insight.sensiolabs.com/projects/f28c2e98-ba1f-468a-9a5c-7ef4fe41a78a"><img src="https://img.shields.io/sensiolabs/i/f28c2e98-ba1f-468a-9a5c-7ef4fe41a78a.svg?style=flat-square" alt="SensioLabsInsight"></a>
    <a href="https://scrutinizer-ci.com/g/spatie/laravel-server-monitor"><img src="https://img.shields.io/scrutinizer/g/spatie/laravel-server-monitor.svg?style=flat-square" alt="Quality Score"></a>
    <a href="https://styleci.io/repos/67774357"><img src="https://styleci.io/repos/67774357/shield?branch=master" alt="StyleCI"></a>
    <a href="https://packagist.org/packages/spatie/laravel-server-monitor"><img src="https://img.shields.io/packagist/dt/spatie/laravel-server-monitor.svg?style=flat-square" alt="Total Downloads"></a>
</section>
