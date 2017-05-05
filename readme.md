# Laravel PHP Framework

[![Build Status](https://travis-ci.org/laravel/framework.svg)](https://travis-ci.org/laravel/framework)
[![Total Downloads](https://poser.pugx.org/laravel/framework/d/total.svg)](https://packagist.org/packages/laravel/framework)
[![Latest Stable Version](https://poser.pugx.org/laravel/framework/v/stable.svg)](https://packagist.org/packages/laravel/framework)
[![Latest Unstable Version](https://poser.pugx.org/laravel/framework/v/unstable.svg)](https://packagist.org/packages/laravel/framework)
[![License](https://poser.pugx.org/laravel/framework/license.svg)](https://packagist.org/packages/laravel/framework)

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable, creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as authentication, routing, sessions, queueing, and caching.

Laravel is accessible, yet powerful, providing tools needed for large, robust applications. A superb inversion of control container, expressive migration system, and tightly integrated unit testing support give you the tools you need to build any application with which you are tasked.

## 路由模型绑定

Laravel 路由模型绑定提供了一个方便的方式来注入类实例到你的路由中.例如，除了注入一个用户的 ID，你也可以注入与指定 ID 相符的完整 User 类实例. [Laravel routing](http://d.laravel-china.org/docs/5.2/routing#route-model-binding).

## 访问次数限制

Laravel 内置的 AuthController 类提供 Illuminate\Foundation\Auth\ThrottlesLogins trait 允许你在应用程序中限制登录次数.默认情况下，如果用户在进行几次尝试后仍不能提供正确的凭证，将在一分钟内无法进行登录.这个限制会特别针对用户的用户名称 / 邮件地址和他们的 IP 地址. [Laravel authentication-throttling](http://d.laravel-china.org/docs/5.2/authentication#authentication-throttling).

## 更简洁快速的实现登录注册

Laravel 通过运行如下命令可快速生成认证所需要的路由和视图：php artisan make:auth
[Laravel authentication](http://d.laravel-china.org/docs/5.2/authentication#路由)

## 多表认证登录（前后台分离）

前台使用user表，后台使用admin表.
