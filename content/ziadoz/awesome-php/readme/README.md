# Awesome Php Overview

A curated list of amazingly awesome PHP libraries, resources and shiny things.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/ziadoz/awesome-php/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 ziadoz/awesome-php](https://github.com/ziadoz/awesome-php) · ⭐ 28K · 🏷️ Programming Languages

[ [Daily](/content/ziadoz/awesome-php/README.md) / [Weekly](/content/ziadoz/awesome-php/week/README.md) / Overview ]

---

# Awesome PHP ![](https://github.com/ziadoz/awesome-php/workflows/Awesome%20Bot/badge.svg)

A curated list of amazingly awesome PHP libraries, resources and shiny things.

## Contributing and Collaborating

Please see [CONTRIBUTING (⭐28k)](https://github.com/ziadoz/awesome-php/blob/master/CONTRIBUTING.md), [CODE-OF-CONDUCT (⭐28k)](https://github.com/ziadoz/awesome-php/blob/master/CODE-OF-CONDUCT.md) and [COLLABORATING (⭐28k)](https://github.com/ziadoz/awesome-php/blob/master/COLLABORATING.md) for details.

## Table of Contents

*   [Awesome PHP](#awesome-php)
    *   [Composer Repositories](#composer-repositories)
    *   [Dependency Management](#dependency-management)
    *   [Dependency Management Extras](#dependency-management-extras)
    *   [Frameworks](#frameworks)
    *   [Framework Extras](#framework-extras)
    *   [Content Management Systems](#content-management-systems-cms)
    *   [Components](#components)
    *   [Micro Frameworks](#micro-frameworks)
    *   [Micro Framework Extras](#micro-framework-extras)
    *   [Routers](#routers)
    *   [Templating](#templating)
    *   [Static Site Generators](#static-site-generators)
    *   [HTTP](#http)
    *   [Scraping](#scraping)
    *   [Middlewares](#middlewares)
    *   [URL](#url)
    *   [Email](#email)
    *   [Files](#Files)
    *   [Streams](#streams)
    *   [Dependency Injection](#dependency-injection)
    *   [Imagery](#imagery)
    *   [Testing](#testing)
    *   [Continuous Integration](#continuous-integration)
    *   [Documentation](#documentation)
    *   [Security](#security)
    *   [Passwords](#passwords)
    *   [Code Analysis](#code-analysis)
    *   [Code Quality](#code-quality)
    *   [Static Analysis](#static-analysis)
    *   [Architectural](#architectural)
    *   [Debugging and Profiling](#debugging-and-profiling)
    *   [Build Tools](#build-tools)
    *   [Task Runners](#task-runners)
    *   [Navigation](#navigation)
    *   [Asset Management](#asset-management)
    *   [Geolocation](#geolocation)
    *   [Date and Time](#date-and-time)
    *   [Event](#event)
    *   [Logging](#logging)
    *   [E-commerce](#e-commerce)
    *   [PDF](#pdf)
    *   [Office](#office)
    *   [Database](#database)
    *   [Migrations](#migrations)
    *   [NoSQL](#nosql)
    *   [Queue](#queue)
    *   [Search](#search)
    *   [Command Line](#command-line)
    *   [Authentication and Authorization](#authentication-and-authorization)
    *   [Markup and CSS](#markup-and-css)
    *   [JSON](#json)
    *   [Strings](#strings)
    *   [Numbers](#numbers)
    *   [Filtering and Validation](#filtering-and-validation)
    *   [API](#api)
    *   [Caching and Locking](#caching-and-locking)
    *   [Data Structure and Storage](#data-structure-and-storage)
    *   [Notifications](#notifications)
    *   [Deployment](#deployment)
    *   [Internationalisation and Localisation](#internationalisation-and-localisation)
    *   [Serverless](#serverless)
    *   [Configuration](#configuration)
    *   [Third Party APIs](#third-party-apis)
    *   [Extensions](#extensions)
    *   [Miscellaneous](#miscellaneous)
*   [Software](#software)
    *   [PHP Installation](#php-installation)
    *   [Development Environment](#development-environment)
    *   [Virtual Machines](#virtual-machines)
    *   [Text Editors and IDEs](#text-editors-and-ides)
    *   [Web Applications](#web-applications)
    *   [Infrastructure](#infrastructure)
*   [Resources](#resources)
    *   [PHP Websites](#php-websites)
    *   [PHP Books](#php-books)
    *   [PHP Videos](#php-videos)
    *   [PHP Podcasts](#php-podcasts)
    *   [PHP Newsletters](#php-newsletters)
    *   [PHP Reading](#php-reading)
    *   [PHP Internals Reading](#php-internals-reading)

### Composer Repositories

*Composer Repositories.*

*   [Firegento](https://packages.firegento.com/) - Magento Module Composer Repository.
*   [Packagist](https://packagist.org/) - The PHP Package Repository.
*   [Private Packagist](https://packagist.com/) - Composer package archive as a service for PHP.
*   [WordPress Packagist](https://wpackagist.org/) - Manage your plugins with Composer.

### Dependency Management

*Libraries for dependency and package management.*

*   [Composer Installers (⭐1.4k)](https://github.com/composer/installers) - A  multi framework Composer library installer.
*   [Composer](https://getcomposer.org/) - A package and dependency manager.
*   [Phive](https://phar.io/) - A PHAR manager.
*   [Pickle (⭐1.6k)](https://github.com/FriendsOfPHP/pickle) - A PHP extension installer.

### Dependency Management Extras

*Extras related to dependency management.*

*   [Composed (⭐49)](https://github.com/joshdifabio/composed) - A library to parse your project's Composer environment at runtime.
*   [Composer Merge Plugin (⭐834)](https://github.com/wikimedia/composer-merge-plugin) - A composer plugin to merge several `composer.json` files.
*   [Composer Normalize (⭐843)](https://github.com/ergebnis/composer-normalize) - A plugin for normalising `composer.json` files.
*   [Composer Patches (⭐1.3k)](https://github.com/cweagans/composer-patches) - A plugin for Composer to apply patches.
*   [Composer Require Checker (⭐701)](https://github.com/maglnet/ComposerRequireChecker) - CLI tool to analyze composer dependencies and verify that no unknown symbols are used in the sources of a package.
*   [Composer Unused (⭐1.1k)](https://github.com/composer-unused/composer-unused) - A CLI Tool to scan for unused composer packages.
*   [Prestissimo (⭐6.3k)](https://github.com/hirak/prestissimo) - A composer plugin which enables parallel install process.
*   [Repman](https://repman.io) - A private PHP package repository manager and Packagist proxy.
*   [Satis (⭐2.9k)](https://github.com/composer/satis) - A static Composer repository generator.
*   [Tooly (⭐100)](https://github.com/tommy-muehle/tooly-composer-script) - A library to manage PHAR files in project using Composer.
*   [Toran Proxy](https://toranproxy.com) - A static Composer repository and proxy.

### Frameworks

*Web development frameworks.*

*   [CakePHP](https://cakephp.org/) - A rapid application development framework.
*   [Laminas](https://getlaminas.org/) - A framework comprised of individual components (previously Zend Framework).
*   [Laravel](https://laravel.com/) - A web application framework with expressive, elegant syntax.
*   [Nette](https://nette.org) - A web framework comprised of mature components.
*   [Phalcon](https://phalcon.io/en-us) - A framework implemented as a C extension.
*   [Spiral](https://spiral.dev/) - A high performance PHP/Go framework.
*   [Symfony](https://symfony.com/) - A set of reusable components and a web framework.
*   [Yii2 (⭐14k)](https://github.com/yiisoft/yii2/) - A fast, secure, and efficient web framework.

### Framework Extras

*Extras related to web development frameworks.*

*   [CakePHP CRUD (⭐352)](https://github.com/friendsofcake/crud) - A Rapid Application Development (RAD) plugin for CakePHP.
*   [Knp RAD Components](https://rad.knplabs.com/) - A set of Rapid Application Development (RAD) components for Symfony.
*   [LaravelS (⭐3.6k)](https://github.com/hhxsv5/laravel-s) - Glue for using Swoole in Laravel or Lumen.
*   [Symfony CMF (⭐734)](https://github.com/symfony-cmf/symfony-cmf) - A Content Management Framework to create custom CMS.
*   [Livewire](https://laravel-livewire.com/) - A full-stack framework for Laravel that takes the pain out of building dynamic UIs.

### Content Management Systems (CMS)

*Tools for managing digital content.*

*   [Backdrop](https://backdropcms.org) - A CMS targeting small-to-medium sized business and non-profits (a fork of Drupal).
*   [Concrete5](https://www.concretecms.com/) - A CMS targeting users with a minimum of technical skills.
*   [CraftCMS (⭐2.9k)](https://github.com/craftcms/cms) - A flexible, user-friendly CMS for creating custom digital experiences on the web and beyond.
*   [Drupal](https://www.drupal.org) - An enterprise level CMS.
*   [Grav (⭐14k)](https://github.com/getgrav/grav) - A modern flat-file CMS.
*   [Joomla](https://www.joomla.org/) - Another leading CMS.
*   [Kirby](https://getkirby.com/) - A flat-file CMS that adapts to any project.
*   [Magento](https://business.adobe.com/products/magento/magento-commerce.html) - The most popular ecommerce platform.
*   [Moodle](https://moodle.org/) - An open-source learning platform.
*   [Pico CMS](https://picocms.org/) - A stupidly simple, blazing fast, flat file CMS.
*   [Statamic](https://statamic.com/) - Build beautiful, easy to manage websites.
*   [WordPress](https://wordpress.org/) - A blogging platform and CMS.

### Components

*Standalone components from web development frameworks and development groups.*

*   [Aura](https://auraphp.com/) - Independent components, fully decoupled from each other and from any framework.
*   [CakePHP Plugins](https://plugins.cakephp.org/) - A directory of CakePHP plugins.
*   [Laravel Components](https://github.com/illuminate) - The Laravel Framework components.
*   [League of Extraordinary Packages](https://thephpleague.com/) - A PHP package development group.
*   [Spatie Open Source](https://spatie.be/open-source) - A collection of open source PHP and Laravel packages.
*   [Symfony Components](https://symfony.com/components) - The components that make Symfony.
*   [Laminas Components](https://docs.laminas.dev/components/) - The components that make the Laminas Framework.

### Micro Frameworks

*Micro frameworks and routers.*

*   [Laravel-Zero](https://laravel-zero.com) - A micro-framework for console applications.
*   [Lumen](https://lumen.laravel.com/) - A micro-framework by Laravel.
*   [Mezzio](https://getexpressive.org/) - A micro-framework by Laminas.
*   [Radar (⭐53)](https://github.com/radarphp/Radar.Adr) - An Action-Domain-Responder implementation for PHP.
*   [Silly (⭐849)](https://github.com/mnapoli/silly) - A micro-framework for CLI applications.
*   [Slim](https://www.slimframework.com/) - Another simple micro framework.

### Micro Framework Extras

*Extras related to micro frameworks and routers.*

*   [Slim Skeleton (⭐1.5k)](https://github.com/slimphp/Slim-Skeleton) - A skeleton for Slim.
*   [Slim Twig View (⭐308)](https://github.com/slimphp/Slim-Views) - Integrate Twig into Slim.
*   [Slim PHP View (⭐232)](https://github.com/slimphp/PHP-View) - A simple PHP renderer for Slim.

### Routers

*Libraries for handling application routing.*

*   [Aura.Router (⭐467)](https://github.com/auraphp/Aura.Router) - A full-featured routing library.
*   [Fast Route (⭐4.7k)](https://github.com/nikic/FastRoute) - A fast routing library.
*   [Klein (⭐2.6k)](https://github.com/klein/klein.php) - A flexible router.
*   [Pux (⭐1.3k)](https://github.com/c9s/Pux) - Another fast routing library.
*   [Route (⭐604)](https://github.com/thephpleague/route) - A routing library built on top of Fast Route.

### Templating

*Libraries and tools for templating and lexing.*

*   [Latte](https://latte.nette.org/) - The safest and truly intuitive templates for PHP.
*   [MtHaml (⭐360)](https://github.com/arnaud-lb/MtHaml) - A PHP implementation of the HAML template language.
*   [Mustache (⭐3.2k)](https://github.com/bobthecow/mustache.php) - A PHP implementation of the Mustache template language.
*   [PHPTAL](https://phptal.org/) - A PHP implementation of the [TAL](https://en.wikipedia.org/wiki/Template_Attribute_Language) templating language.
*   [Plates](http://platesphp.com/) - A native PHP templating library.
*   [Smarty](https://www.smarty.net/) - A template engine to complement PHP.
*   [Twig](https://twig.symfony.com/) - A comprehensive templating language.

### Static Site Generators

*Tools for pre-processing content to generate web pages.*

*   [Couscous](http://couscous.io) - Couscous turns Markdown documentation into beautiful websites. It's GitHub Pages on steroids.
*   [Jigsaw](https://jigsaw.tighten.com/) - Simple static sites with Laravel's Blade.
*   [Sculpin](https://sculpin.io) - A tool that converts Markdown and Twig into static HTML.
*   [Spress](http://spress.yosymfony.com) - An extensible tool that converts Markdown and Twig into HTML.

### HTTP

*Libraries for working with HTTP.*

*   [Buzz (⭐1.9k)](https://github.com/kriswallsmith/Buzz) - Another HTTP client.
*   [Guzzle (⭐22k)](https://github.com/guzzle/guzzle) - A comprehensive HTTP client.
*   [HTTPlug](http://httplug.io) - An HTTP client abstraction without binding to a specific implementation.
*   [Nyholm PSR-7 (⭐951)](https://github.com/Nyholm/psr7) - A super lightweight PSR-7 implementation. Very strict and very fast.
*   [PHP VCR](https://php-vcr.github.io/) - A library for recording and replaying HTTP requests.
*   [Requests (⭐3.5k)](https://github.com/WordPress/Requests) - A simple HTTP library.
*   [Retrofit (⭐153)](https://github.com/tebru/retrofit-php) - A library to ease creation of REST API clients.
*   [Symfony HTTP Client (⭐1.6k)](https://github.com/symfony/http-client) - A component to fetch HTTP resources synchronously or asynchronously.
*   [Laminas Diactoros (⭐333)](https://github.com/laminas/laminas-diactoros) - PSR-7 HTTP Message implementation.

### Scraping

*Libraries for scraping websites.*

*   [Chrome PHP (⭐1.6k)](https://github.com/chrome-php/chrome) - Instrument headless Chrome/Chromium instances from PHP.
*   [DiDOM (⭐2k)](https://github.com/Imangazaliev/DiDOM) - A super fast HTML scrapper and parser.
*   [Embed (⭐1.9k)](https://github.com/oscarotero/Embed) - An information extractor from any web service or page.
*   [Goutte (⭐9.1k)](https://github.com/FriendsOfPHP/Goutte) - A simple web scraper.
*   [Symfony Panther (⭐2.6k)](https://github.com/symfony/panther) - A browser testing and web crawling library for PHP and Symfony.
*   [PHP Spider (⭐1.3k)](https://github.com/mvdbos/php-spider) - A configurable and extensible PHP web spider.

### Middlewares

*Libraries for building application using middlewares.*

*   [PSR-7 Middlewares (⭐657)](https://github.com/oscarotero/psr7-middlewares) - Inspiring collection of handy middlewares.
*   [Relay (⭐297)](https://github.com/relayphp/Relay.Relay) - A PHP 5.5 PSR-7 middleware dispatcher.
*   [Stack](https://github.com/stackphp) - A library of stackable middleware for Symfony.
*   [Laminas Stratigility (⭐44)](https://github.com/laminas/laminas-stratigility) - Middleware for PHP built on top of PSR-7.

### URL

*Libraries for parsing URLs.*

*   [PHP Domain Parser (⭐1k)](https://github.com/jeremykendall/php-domain-parser) - A domain suffix parser library.
*   [Purl (⭐908)](https://github.com/jwage/purl) - A URL manipulation library.
*   [sabre/uri (⭐284)](https://github.com/sabre-io/uri) - A functional URI manipulation library.
*   [Uri (⭐857)](https://github.com/thephpleague/uri) - Another URL manipulation library.

### Email

*Libraries for sending and parsing email.*

*   [CssToInlineStyles (⭐5.6k)](https://github.com/tijsverkoyen/CssToInlineStyles) - A library to inline CSS in email templates.
*   [Email Reply Parser (⭐603)](https://github.com/willdurand/EmailReplyParser) - An email reply parser library.
*   [Email Validator (⭐155)](https://github.com/nojacko/email-validator) - A small email address validation library.
*   [Fetch (⭐500)](https://github.com/tedious/Fetch) - An IMAP library.
*   [Mautic (⭐5.5k)](https://github.com/mautic/mautic) - Email marketing automation
*   [PHPMailer (⭐19k)](https://github.com/PHPMailer/PHPMailer) - Another mailer solution.
*   [PHP IMAP (⭐1.5k)](https://github.com/barbushin/php-imap) - A library to access mailboxes via POP3, IMAP and NNTP.
*   [Stampie (⭐287)](https://github.com/Stampie/Stampie) - A library for email services such as [SendGrid](https://sendgrid.com/), [PostMark](https://postmarkapp.com), [MailGun](https://www.mailgun.com/) and [MailChimp](https://mailchimp.com/features/transactional-email/).
*   [SwiftMailer](https://swiftmailer.symfony.com) - A mailer solution.
*   [Symfony Mailer (⭐1.1k)](https://github.com/symfony/mailer) - A powerful library for creating and sending emails.

### Files

*Libraries for file manipulation and MIME type detection.*

*   [CSV (⭐3k)](https://github.com/thephpleague/csv) - A CSV data manipulation library.
*   [Flysystem (⭐13k)](https://github.com/thephpleague/Flysystem) - Abstraction for local and remote filesystems.
*   [Gaufrette (⭐2.4k)](https://github.com/KnpLabs/Gaufrette) - A filesystem abstraction layer.
*   [PHP FFmpeg (⭐4.3k)](https://github.com/PHP-FFmpeg/PHP-FFmpeg/) - A wrapper for the [FFmpeg](https://www.ffmpeg.org/) video library.
*   [UnifiedArchive (⭐264)](https://github.com/wapmorgan/UnifiedArchive) - A unified reader and writer of compressed archives.

### Streams

*Libraries for working with streams.*

*   [ByteStream](https://amphp.org/byte-stream/) - An asynchronous stream abstraction.
*   [Streamer (⭐269)](https://github.com/fzaninotto/Streamer) - A simple object-orientated stream wrapper library.

### Dependency Injection

*Libraries that implement the dependency injection design pattern.*

*   [Aura.Di (⭐342)](https://github.com/auraphp/Aura.Di) - A serializable dependency injection container with constructor and setter injection, interface and trait awareness, configuration inheritance, and much more.
*   [Acclimate (⭐217)](https://github.com/AcclimateContainer/acclimate-container) - A common interface to dependency injection containers and service locators.
*   [Auryn (⭐723)](https://github.com/rdlowrey/Auryn) - A recursive dependency injector.
*   [Container (⭐774)](https://github.com/thephpleague/container) - Another flexible dependency injection container.
*   [Disco (⭐137)](https://github.com/bitExpert/disco) - A PSR-11 compatible, annotation-based dependency injection container.
*   [PHP-DI](https://php-di.org/) - A dependency injection container that supports autowiring.
*   [Pimple](https://pimple.symfony.com/) - A tiny dependency injection container.
*   [Symfony DI (⭐3.8k)](https://github.com/symfony/dependency-injection) - A dependency injection container component.

### Imagery

*Libraries for manipulating images.*

*   [Color Extractor (⭐1.2k)](https://github.com/thephpleague/color-extractor) - A library for extracting colours from images.
*   [Glide (⭐2.4k)](https://github.com/thephpleague/glide) - An on-demand image manipulation library.
*   [Image Hash (⭐1.8k)](https://github.com/jenssegers/imagehash) - A library for generating perceptual image hashes.
*   [Image Optimizer (⭐874)](https://github.com/psliwa/image-optimizer) - A library for optimizing images.
*   [Imagine](https://imagine.readthedocs.io/en/latest/index.html) - An image manipulation library.
*   [Intervention Image (⭐13k)](https://github.com/Intervention/image) - Another image manipulation library.
*   [PHP Image Workshop (⭐856)](https://github.com/Sybio/ImageWorkshop) - Another image manipulation library.

### Testing

*Libraries for testing codebases and generating test data.*

*   [Alice (⭐2.4k)](https://github.com/nelmio/alice) - An expressive fixture generation library.
*   [AspectMock (⭐774)](https://github.com/Codeception/AspectMock) - A mocking framework for PHPUnit/Codeception.
*   [Atoum (⭐1.4k)](https://github.com/atoum/atoum) - A simple testing library.
*   [Behat](https://docs.behat.org/en/latest/) - A behaviour driven development (BDD) testing framework.
*   [Codeception (⭐4.6k)](https://github.com/Codeception/Codeception) - A full stack testing framework.
*   [Faker (⭐2.6k)](https://github.com/fakerphp/faker) - A fake data generator library.
*   [Foundry (⭐451)](https://github.com/zenstruck/foundry) - A fixture factory generation library for Doctrine.
*   [HTTP Mock (⭐387)](https://github.com/InterNations/http-mock) - A library for mocking HTTP requests in unit tests.
*   [Infection (⭐1.8k)](https://github.com/infection/infection) - An AST-based PHP Mutation testing framework.
*   [Kahlan (⭐1.1k)](https://github.com/kahlan/kahlan) - Full stack Unit/BDD testing framework with built-in stub, mock and code-coverage support.
*   [Mink](https://mink.behat.org/en/latest/) - Web acceptance testing.
*   [Mockery (⭐10k)](https://github.com/mockery/mockery) - A mock object library for testing.
*   [ParaTest (⭐2k)](https://github.com/paratestphp/paratest) - A parallel testing library for PHPUnit.
*   [Pest](https://pestphp.com/) - A testing framework with a focus on simplicity.
*   [Peridot (⭐326)](https://github.com/peridot-php/peridot) - An event driven test framework.
*   [Phake (⭐467)](https://github.com/phake/phake) - Another mock object library for testing.
*   [Pho (⭐285)](https://github.com/danielstjules/pho) - Another behaviour driven development testing framework.
*   [PHP-Mock (⭐328)](https://github.com/php-mock/php-mock) - A mock library for built-in PHP functions (e.g. time()).
*   [PHP MySQL Engine (⭐521)](https://github.com/vimeo/php-mysql-engine) -  A MySQL engine written in pure PHP.
*   [PHPSpec (⭐1.8k)](https://github.com/phpspec/phpspec) - A design by specification unit testing library.
*   [PHPT](https://qa.php.net/write-test.php) - A test tool used by PHP itself.
*   [PHPUnit (⭐19k)](https://github.com/sebastianbergmann/phpunit) - A unit testing framework.
*   [Prophecy (⭐8.5k)](https://github.com/phpspec/prophecy) - A highly opinionated mocking framework.
*   [VFS Stream (⭐1.3k)](https://github.com/bovigo/vfsStream) - A virtual filesystem stream wrapper for testing.

### Continuous Integration

*Libraries and applications for continuous integration.*

*   [CircleCI](https://circleci.com) - A continuous integration platform.
*   [GitlabCi](https://about.gitlab.com/stages-devops-lifecycle/continuous-integration/) - Let GitLab CI test, build, deploy your code. TravisCi like.
*   [Jenkins](https://www.jenkins.io/) - A continuous integration platform with [PHP support](https://www.jenkins.io/solutions/php/).
*   [JoliCi (⭐660)](https://github.com/jolicode/JoliCi) - A continuous integration client written in PHP and powered by Docker.
*   [PHPCI (⭐2.4k)](https://github.com/dancryer/phpci) - An open source continuous integration platform for PHP.
*   [SemaphoreCI](https://semaphoreci.com/) - A continuous integration platform for open source and private projects.
*   [Shippable](https://jfrog.com/blog/weve-acquired-shippable-to-complete-devops-pipeline-automation-from-code-to-production/) - A Docker based continious integration platform for open source and private projects.
*   [Travis CI](https://travis-ci.org/) - A continuous integration platform.
*   [Setup PHP (⭐2.3k)](https://github.com/shivammathur/setup-php) - A GitHub Action for PHP.

### Documentation

*Libraries for generating project documentation.*

*   [APIGen (⭐2.1k)](https://github.com/apigen/apigen) - Another API documentation generator.
*   [daux.io (⭐713)](https://github.com/dauxio/daux.io) - A documentation generator which uses Markdown files.
*   [PHP Documentor 2 (⭐3.7k)](https://github.com/phpDocumentor/phpDocumentor) - A documentation generator.
*   [phpDox](https://phpdox.net/) - A documentation generator for PHP projects (that is not limited to API documentation).

### Security

*Libraries for generating secure random numbers, encrypting data and scanning and testing for vulnerabilities.*

*   [Halite](https://paragonie.com/project/halite) - A simple library for encryption using [libsodium (⭐11k)](https://github.com/jedisct1/libsodium).
*   [HTML Purifier (⭐2.6k)](https://github.com/ezyang/htmlpurifier) - A standards compliant HTML filter.
*   [IniScan (⭐1.5k)](https://github.com/psecio/iniscan) - A tool that scans PHP INI files for security.
*   [Optimus (⭐1.2k)](https://github.com/jenssegers/optimus) - Id obfuscation based on Knuth's multiplicative hashing method.
*   [PHPGGC (⭐2.4k)](https://github.com/ambionics/phpggc) - A library of PHP unserializable payloads along with a tool to generate them.
*   [PHP Encryption (⭐3.5k)](https://github.com/defuse/php-encryption) - Secure PHP Encryption Library.
*   [PHP SSH (⭐353)](https://github.com/Herzult/php-ssh) - An experimental object orientated SSH wrapper library.
*   [PHPSecLib](http://phpseclib.sourceforge.net/) - A pure PHP secure communications library.
*   [random\_compat (⭐8k)](https://github.com/paragonie/random_compat) - PHP 5.x support for `random_bytes()` and `random_int()`
*   [RandomLib (⭐831)](https://github.com/ircmaxell/RandomLib) - A library for generating random numbers and strings.
*   [Symfony Security Monitoring](https://security.symfony.com/) - A web tool to check your Composer dependencies for security advisories, previously known as "SensioLabs Security Check".
*   [SQLMap (⭐25k)](https://github.com/sqlmapproject/sqlmap) - An automatic SQL injection and database takeover tool.
*   [TCrypto (⭐56)](https://github.com/timoh6/TCrypto) - A simple encrypted key-value storage library.
*   [VAddy](https://vaddy.net/) - A continuous security testing platform for web applications.
*   [Zap](https://owasp.org/www-project-zap/) - An integrated penetration testing tool for web applications.

### Passwords

*Libraries and tools for working with and storing passwords.*

*   [GenPhrase (⭐111)](https://github.com/timoh6/GenPhrase) - A library for generating secure random passphrases.
*   [Password Compat (⭐2.2k)](https://github.com/ircmaxell/password_compat) - A compatibility library for the new PHP 5.5 password functions.
*   [Password Policy (⭐74)](https://github.com/ircmaxell/password-policy) - A password policy library for PHP and JavaScript.
*   [Password Validator (⭐142)](https://github.com/jeremykendall/password-validator) - A library for validating and upgrading password hashes.
*   [Password-Generator (⭐253)](https://github.com/hackzilla/password-generator) - PHP library to generate random passwords.
*   [PHP Password Lib (⭐372)](https://github.com/ircmaxell/PHP-PasswordLib) - A library for generating and validating passwords.
*   [phpass](https://www.openwall.com/phpass/) - A portable password hashing framework.
*   [Zxcvbn PHP (⭐758)](https://github.com/bjeavons/zxcvbn-php) - A realistic PHP password strength estimate library based on Zxcvbn JS.

### Code Analysis

*Libraries and tools for analysing, parsing and manipulating codebases.*

*   [Better Reflection (⭐1.1k)](https://github.com/Roave/BetterReflection) - AST-based reflection library that allows analysis and manipulation of code
*   [Code Climate](https://codeclimate.com) - An automated code review.
*   [GrumPHP (⭐3.8k)](https://github.com/phpro/grumphp) - A PHP code-quality tool.
*   [PHP Parser (⭐16k)](https://github.com/nikic/PHP-Parser) - A PHP parser written in PHP.
*   [PHP Semantic Versioning Checker (⭐424)](https://github.com/tomzx/php-semver-checker) - A command line utility that compares two source sets and determines the appropriate semantic versioning to apply.
*   [Phpactor (⭐830)](https://github.com/phpactor/phpactor) - PHP completion, refactoring and introspection tool.
*   [PHPLOC (⭐2.3k)](https://github.com/sebastianbergmann/phploc) - A tool for quickly measuring the size of a PHP project.
*   [PHPQA (⭐539)](https://github.com/EdgedesignCZ/phpqa) - A tool for running QA tools (phploc, phpcpd, phpcs, pdepend, phpmd, phpmetrics).
*   [Qafoo Quality Analyzer (⭐495)](https://github.com/Qafoo/QualityAnalyzer) - A tool to visualize metrics and source code.
*   [Rector (⭐6.1k)](https://github.com/rectorphp/rector) - A tool to upgrade and refactor code.
*   [Scrutinizer](https://scrutinizer-ci.com/) - A web tool to [scrutinise PHP code (⭐443)](https://github.com/scrutinizer-ci/php-analyzer).
*   [UBench (⭐555)](https://github.com/devster/ubench) - A simple micro benchmark library.

### Code Quality

*Libraries for managing code quality, formatting and linting.*

*   [CaptainHook (⭐787)](https://github.com/captainhookphp/captainhook) - An easy-to-use and flexible Git hook library.
*   [PHP CodeSniffer (⭐9.8k)](https://github.com/squizlabs/PHP_CodeSniffer) - A library that detects PHP, CSS and JS coding standard violations.
*   [PHP CS Fixer (⭐11k)](https://github.com/FriendsOfPHP/PHP-CS-Fixer) - A coding standards fixer library.
*   [PHP Mess Detector (⭐2.1k)](https://github.com/phpmd/phpmd) - A library that scans code for bugs, sub-optimal code, unused parameters and more.
*   [PHPCheckstyle (⭐156)](https://github.com/PHPCheckstyle/phpcheckstyle) - A tool to help adhere to certain coding conventions.
*   [PHPCPD (⭐2.2k)](https://github.com/sebastianbergmann/phpcpd) - A library that detects copied and pasted code.

### Static Analysis

*Libraries for performing static analysis of PHP code.*

*   [Exakat (⭐368)](https://github.com/exakat/exakat) - A static analysis engine for PHP.
*   [Deptrac (⭐2.1k)](https://github.com/qossmic/deptrac) - A static code analysis tool that helps to enforce rules for dependencies between software layers.
*   [Mondrian (⭐391)](https://github.com/Trismegiste/Mondrian) - A code analysis tool using Graph Theory.
*   [phan (⭐5.3k)](https://github.com/phan/phan) - A static analyzer based on PHP 7+ and the php-ast extension.
*   [PHP Architecture Tester (⭐743)](https://github.com/carlosas/phpat) - Easy to use architecture testing tool for PHP.
*   [PHPCompatibility (⭐1.9k)](https://github.com/PHPCompatibility/PHPCompatibility) - A PHP compatibility checker for PHP CodeSniffer.
*   [PhpDependencyAnalysis (⭐545)](https://github.com/mamuz/PhpDependencyAnalysis) - A tool to create customisable dependency graphs.
*   [PHP Metrics (⭐2.3k)](https://github.com/phpmetrics/PhpMetrics) - A static metric library.
*   [PHP Migration (⭐194)](https://github.com/monque/PHP-Migration) - A static analyzer for PHP version migration.
*   [PHPStan (⭐11k)](https://github.com/phpstan/phpstan) - A PHP Static Analysis Tool.
*   [Psalm (⭐4.9k)](https://github.com/vimeo/psalm) - A static analysis tool for finding errors in PHP applications.

### Architectural

*Libraries related to design patterns, programming approaches and ways to organize code.*

*   [Design Patterns PHP (⭐21k)](https://github.com/DesignPatternsPHP/DesignPatternsPHP) - A repository of software patterns implemented in PHP.
*   [Finite](https://yohan.giarel.li/Finite/) - A simple PHP finite state machine.
*   [Functional PHP (⭐1.9k)](https://github.com/lstrojny/functional-php) - A functional programming library.
*   [Iter (⭐1.1k)](https://github.com/nikic/iter) - A library that provides iteration primitives using generators.
*   [Patchwork](https://patchwork2.org/) - A library for redefining userland functions.
*   [Pipeline (⭐867)](https://github.com/thephpleague/pipeline) - A pipeline pattern implementation.
*   [Porter (⭐556)](https://github.com/ScriptFUSION/Porter) - Data import abstraction library for consuming Web APIs and other data sources.
*   [RulerZ (⭐864)](https://github.com/K-Phoen/rulerz) - A powerful rule engine and implementation of the Specification pattern.

### Debugging and Profiling

*Libraries and tools for debugging errors and profiling code.*

*   [APM](https://pecl.php.net/package/APM) - Monitoring extension collecting errors and statistics into SQLite/MySQL/StatsD.
*   [Barbushin PHP Console (⭐1.4k)](https://github.com/barbushin/php-console) - Another web debugging console using Google Chrome.
*   [Blackfire.io](https://www.blackfire.io) - A low-overhead code profiler.
*   [Kint (⭐2.6k)](https://github.com/kint-php/kint) - A debugging and profiling tool.
*   [Metrics (⭐313)](https://github.com/beberlei/metrics) - A simple metrics API library.
*   [PCOV (⭐598)](https://github.com/krakjoe/pcov) - A self contained code coverage compatible driver.
*   [PHP Console (⭐523)](https://github.com/Seldaek/php-console) - A web debugging console.
*   [PHP Debug Bar](http://phpdebugbar.com/) - A debugging toolbar.
*   [PHPBench (⭐1.6k)](https://github.com/phpbench/phpbench) - A benchmarking Framework.
*   [PHPSpy (⭐1.3k)](https://github.com/adsr/phpspy) - A low-overhead sampling profiler.
*   [Symfony VarDumper (⭐7.1k)](https://github.com/symfony/var-dumper) - A variable dumper component.
*   [Tideways.io](https://tideways.com/) - Monitoring and profiling tool.
*   [Tracy (⭐1.6k)](https://github.com/nette/tracy) - A simple error detection, logging and time measuring library.
*   [Whoops (⭐13k)](https://github.com/filp/whoops) - A pretty error handling library.
*   [xDebug (⭐2.7k)](https://github.com/xdebug/xdebug) - A debug and profile tool for PHP.
*   [XHProf (⭐2.5k)](https://github.com/phacility/xhprof) - A profiling tool originally developed by Facebook.
*   [Z-Ray](https://www.zend.com/products/z-ray) - A debug and profile tool for Zend Server.

### Build Tools

*Project build and automation tools.*

*   [Box (⭐839)](https://github.com/box-project/box) - A utility to build PHAR files.
*   [Construct (⭐263)](https://github.com/jonathantorres/construct) - A PHP project/micro-package generator.
*   [Phing](https://www.phing.info/) - A PHP project build system inspired by Apache Ant.
*   [RMT (⭐441)](https://github.com/liip/RMT) - A library for versioning and releasing software.

### Task Runners

*Libraries for automating and running tasks.*

*   [Bldr](https://bldr.io/) - A PHP Task runner built on Symfony components.
*   [Jobby (⭐1k)](https://github.com/jobbyphp/jobby) - A PHP cron job manager without modifying crontab.
*   [Robo (⭐2.6k)](https://github.com/consolidation/Robo) - A PHP Task runner with object-orientated configurations.
*   [Task](https://taskphp.github.io/) - A pure PHP task runner inspired by Grunt and Gulp.

### Navigation

*Tools for building navigation structures.*

*   [KnpMenu (⭐1.3k)](https://github.com/KnpLabs/KnpMenu) - A menu library.
*   [Menu (⭐647)](https://github.com/spatie/menu) - A flexible menu library with a fluent interface.

### Asset Management

*Tools for managing, compressing and minifying website assets.*

*   [JShrink (⭐676)](https://github.com/tedious/JShrink) - A JavaScript minifier library.
*   [Laravel Mix (⭐5.1k)](https://github.com/laravel-mix/laravel-mix) - An elegant wrapper around Webpack for the 80% use case.
*   [Symfony Asset (⭐2.9k)](https://github.com/symfony/asset) - Manages URL generation and versioning of web assets.
*   [Symfony Encore (⭐2.1k)](https://github.com/symfony/webpack-encore) - A simple but powerful API for processing and compiling assets built around Webpack.

### Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

*   [Country List (⭐5k)](https://github.com/umpirsky/country-list) - A list of all countries with names and ISO 3166-1 codes.
*   [GeoCoder](https://geocoder-php.org/) - A geocoding library.
*   [GeoJSON (⭐273)](https://github.com/jmikola/geojson) - A GeoJSON implementation.
*   [GeoTools (⭐1.3k)](https://github.com/thephpleague/geotools) - A library of geo-related tools.
*   [PHPGeo (⭐1.4k)](https://github.com/mjaschen/phpgeo) - A simple geo library.

### Date and Time

*Libraries for working with dates and times.*

*   [CalendR](https://yohan.giarel.li/CalendR/) - A calendar management library.
*   [Carbon (⭐16k)](https://github.com/briannesbitt/Carbon) - A simple DateTime API extension.
*   [Chronos (⭐1.3k)](https://github.com/cakephp/chronos) - A DateTime API extension supporting both mutable and immutable date/time.
*   [Moment.php (⭐946)](https://github.com/fightbulc/moment.php) - Moment.js inspired PHP DateTime handler with i18n support.
*   [Yasumi (⭐899)](https://github.com/azuyalabs/yasumi) - An library to help you calculate the dates and names of holidays.

### Event

*Libraries that are event-driven or implement non-blocking event loops.*

*   [Amp (⭐3.7k)](https://github.com/amphp/amp) - An event driven non-blocking I/O library.
*   [Broadway (⭐1.4k)](https://github.com/broadway/broadway) - An event source and CQRS library.
*   [CakePHP Event (⭐21)](https://github.com/cakephp/event) - An event dispatcher library.
*   [Elephant.io (⭐1.2k)](https://github.com/Wisembly/Elephant.io) - Yet another web socket library.
*   [Evenement (⭐1.2k)](https://github.com/igorw/evenement) - An event dispatcher library.
*   [Event (⭐1.4k)](https://github.com/thephpleague/event) - An event library with a focus on domain events.
*   [Pawl (⭐524)](https://github.com/ratchetphp/Pawl) - An asynchronous web socket client.
*   [Prooph Event Store (⭐531)](https://github.com/prooph/event-store) - An event source component to persist event messages
*   [PHP Defer (⭐241)](https://github.com/php-defer/php-defer) - Golang's defer statement for PHP.
*   [Ratchet (⭐5.8k)](https://github.com/ratchetphp/Ratchet) - A web socket library.
*   [ReactPHP (⭐8.4k)](https://github.com/reactphp/reactphp) - An event driven non-blocking I/O library.
*   [RxPHP (⭐1.6k)](https://github.com/ReactiveX/RxPHP) - A reactive extension library.
*   [Swoole (⭐18k)](https://github.com/swoole/swoole-src) - An event-driven asynchronous and concurrent networking communication framework with high performance for PHP written in C.
*   [Workerman (⭐10k)](https://github.com/walkor/Workerman) - An event driven non-blocking I/O library.

### Logging

*Libraries for generating and working with log files.*

*   [Monolog (⭐20k)](https://github.com/Seldaek/monolog) - A comprehensive logger.

### E-commerce

*Libraries and applications for taking payments and building online e-commerce stores.*

*   [Money (⭐4.1k)](https://github.com/moneyphp/money) - A PHP implementation of Fowler's money pattern.
*   [Brick\Money (⭐1.2k)](https://github.com/brick/money) - A money library for PHP, with support for contexts, cash roundings, currency conversion.
*   [OmniPay (⭐5.6k)](https://github.com/thephpleague/omnipay) - A framework agnostic multi-gateway payment processing library.
*   [Payum (⭐1.7k)](https://github.com/payum/payum) - A payment abstraction library.
*   [Shopware (⭐1.3k)](https://github.com/shopware/shopware) - Highly customizable e-commerce software
*   [Swap (⭐1.3k)](https://github.com/florianv/swap) - An exchange rates library.
*   [Sylius](https://sylius.com/) - An open source e-commerce solution.

### PDF

*Libraries and software for working with PDF files.*

*   [Dompdf (⭐9.2k)](https://github.com/dompdf/dompdf) - A HTML to PDF converter.
*   [PHPPdf (⭐336)](https://github.com/psliwa/PHPPdf) - A library for generating PDFs and images from XML.
*   [Snappy (⭐4.1k)](https://github.com/KnpLabs/snappy) - A PDF and image generation library.
*   [WKHTMLToPDF (⭐13k)](https://github.com/wkhtmltopdf/wkhtmltopdf) - A tool to convert HTML to PDF.

### Office

*Libraries for working with office suite documents.*

*   [PHPPowerPoint (⭐1.2k)](https://github.com/PHPOffice/PHPPresentation) - A library for working with Microsoft PowerPoint Presentations.
*   [PHPWord (⭐6.4k)](https://github.com/PHPOffice/PHPWord) - A library for working with Microsoft Word documents.
*   [PHPSpreadsheet (⭐12k)](https://github.com/PHPOffice/PhpSpreadsheet) - A pure PHP library for reading and writing spreadsheet files (successor of PHPExcel).
*   [Spout (⭐4.2k)](https://github.com/box/spout) - Read and write spreadsheet files (CSV, XLSX and ODS), in a fast and scalable way .

### Database

*Libraries for interacting with databases using object-relational mapping (ORM) or datamapping techniques.*

*   [Atlas.Orm (⭐428)](https://github.com/atlasphp/Atlas.Orm) - A data mapper implementation for your persistence model in PHP.
*   [Aura.Sql (⭐531)](https://github.com/auraphp/Aura.Sql) - Provides an extension to the native PDO along with a profiler and connection locator.
*   [Aura.SqlQuery (⭐421)](https://github.com/auraphp/Aura.SqlQuery) - Independent query builders for MySQL, PostgreSQL, SQLite, and Microsoft SQL Server.
*   [Baum (⭐2.2k)](https://github.com/etrepat/baum) - A nested set implementation for Eloquent.
*   [CakePHP ORM (⭐146)](https://github.com/cakephp/orm) - Object-Relational Mapper, implemented using the DataMapper pattern.
*   [Cycle ORM (⭐1.1k)](https://github.com/cycle/orm) - PHP DataMapper, ORM.
*   [Doctrine Extensions (⭐3.8k)](https://github.com/doctrine-extensions/DoctrineExtensions) - A collection of Doctrine behavioural extensions.
*   [Doctrine](https://www.doctrine-project.org/) - A comprehensive DBAL and ORM.
*   [Laravel Eloquent (⭐2.5k)](https://github.com/illuminate/database) - A simple ORM.
*   [Pomm (⭐161)](https://github.com/chanmix51/Pomm) - An Object Model Manager for PostgreSQL.
*   [ProxyManager (⭐4.8k)](https://github.com/Ocramius/ProxyManager) - A set of utilities to generate proxy objects for data mappers.
*   [RedBean](https://redbeanphp.com/index.php) - A lightweight, configuration-less ORM.
*   [Slimdump (⭐176)](https://github.com/webfactory/slimdump) - An easy dumper tool for MySQL.
*   [Spot2 (⭐603)](https://github.com/spotorm/spot2) - A MySQL datamapper ORM.

### Migrations

Libraries to help manage database schemas and migrations.

*   [Doctrine Migrations](https://www.doctrine-project.org/projects/migrations.html) - A migration library for Doctrine.
*   [Migrations (⭐38)](https://github.com/icomefromthenet/Migrations) - A migration management library.
*   [Phinx (⭐4.3k)](https://github.com/cakephp/phinx) - Another database migration library.
*   [PHPMig (⭐559)](https://github.com/davedevelopment/phpmig) - Another migration management library.
*   [Ruckusing (⭐507)](https://github.com/ruckus/ruckusing-migrations) - Database migrations for PHP ala ActiveRecord Migrations with support for MySQL, Postgres, SQLite.

### NoSQL

*Libraries for working with "NoSQL" backends.*

*   [PHPMongo (⭐238)](https://github.com/sokil/php-mongo) - A MongoDB ORM.
*   [Predis (⭐7.2k)](https://github.com/predis/predis) - A feature complete Redis library.

### Queue

*Libraries for working with event and task queues.*

*   [Bernard (⭐1.2k)](https://github.com/bernardphp/bernard) - A multibackend abstraction library.
*   [BunnyPHP (⭐628)](https://github.com/jakubkulhan/bunny) - A performant pure-PHP AMQP (RabbitMQ) sync and also async (ReactPHP) library.
*   [Pheanstalk (⭐1.9k)](https://github.com/pheanstalk/pheanstalk) - A Beanstalkd client library.
*   [PHP AMQP (⭐4.2k)](https://github.com/php-amqplib/php-amqplib) - A pure PHP AMQP library.
*   [Tarantool Queue (⭐62)](https://github.com/tarantool-php/queue) - PHP bindings for Tarantool Queue.
*   [Thumper (⭐276)](https://github.com/php-amqplib/Thumper) - A RabbitMQ pattern library.
*   [Enqueue (⭐2.1k)](https://github.com/php-enqueue/enqueue-dev) - A message queue packages for PHP that supports RabbitMQ, AMQP, STOMP, Amazon SQS, Redis and Doctrine transports.

### Search

*Libraries and software for indexing and performing search queries on data.*

*   [Elastica (⭐2.2k)](https://github.com/ruflin/Elastica) - A client library for ElasticSearch.
*   [ElasticSearch PHP (⭐5k)](https://github.com/elastic/elasticsearch-php) - The official client library for [ElasticSearch](https://www.elastic.co/).
*   [Solarium](https://www.solarium-project.org/) - A client library for [Solr](https://solr.apache.org/).
*   [SphinxQL Query Builder](https://foolcode.github.io/SphinxQL-Query-Builder/) - A query library for the [Sphinx](https://sphinxsearch.com/) and [Manticore](https://manticoresearch.com/) search engines.

### Command Line

*Libraries related to the command line.*

*   [Aura.Cli (⭐103)](https://github.com/auraphp/Aura.Cli) - Provides the equivalent of request ( Context ) and response ( Stdio ) objects for the command line interface, including Getopt support, and an independent Help object for describing commands.
*   [Boris (⭐2.2k)](https://github.com/borisrepl/boris) - A tiny PHP REPL.
*   [Cilex (⭐623)](https://github.com/Cilex/Cilex) - A micro framework for building command line tools.
*   [CLI Menu (⭐1.9k)](https://github.com/php-school/cli-menu) - A library for building CLI menus.
*   [CLIFramework (⭐424)](https://github.com/c9s/CLIFramework) - A command-line framework supports zsh/bash completion generation, subcommands and option constraints. It also powers phpbrew.
*   [CLImate (⭐1.8k)](https://github.com/thephpleague/climate) - A library for outputting colours and special formatting.
*   [Commando (⭐791)](https://github.com/nategood/commando) - Another simple command line opt parser.
*   [Cron Expression (⭐4.9k)](https://github.com/mtdowling/cron-expression) - A library to calculate cron run dates.
*   [GetOpt (⭐321)](https://github.com/getopt-php/getopt-php) - A command line opt parser.
*   [GetOptionKit (⭐140)](https://github.com/c9s/GetOptionKit) - Another command line opt parser.
*   [PsySH (⭐9.4k)](https://github.com/bobthecow/psysh) - Another PHP REPL.
*   [ShellWrap (⭐743)](https://github.com/MrRio/shellwrap) - A simple command line wrapper library.

### Authentication and Authorization

*Libraries for implementing user authentication and authorization.*

*   [Aura.Auth (⭐125)](https://github.com/auraphp/Aura.Auth) - Provides authentication functionality and session tracking using various adapters.
*   [SocialConnect Auth (⭐511)](https://github.com/socialConnect/auth) - An open source social sign (OAuth1\OAuth2\OpenID\OpenIDConnect).
*   [Json Web Token (⭐6.8k)](https://github.com/lcobucci/jwt) - Json Tokens to authenticate and transmit information.
*   [OAuth 1.0 Client (⭐900)](https://github.com/thephpleague/oauth1-client) - An OAuth 1.0 client library.
*   [OAuth 2.0 Client (⭐3.3k)](https://github.com/thephpleague/oauth2-client) - An OAuth 2.0 client library.
*   [OAuth2 Server](https://bshaffer.github.io/oauth2-server-php-docs/) - Another OAuth2 server implementation.
*   [OAuth2 Server](https://oauth2.thephpleague.com/) - An OAuth2 authentication server, resource server and client library.
*   [Opauth (⭐1.7k)](https://github.com/opauth/opauth) - A multi-provider authentication framework.
*   [Paseto (⭐3.1k)](https://github.com/paragonie/paseto) - Platform-Agnostic Security Tokens.
*   [PHP oAuthLib (⭐1.1k)](https://github.com/Lusitanian/PHPoAuthLib) - Another OAuth library.
*   [Sentinel Social](https://cartalyst.com/manual/sentinel-social/2.0) - A library for social network authentication.
*   [Sentinel](https://cartalyst.com/manual/sentinel/2.0) - A framework agnostic authentication & authorisation library.
*   [TwitterOAuth (⭐4.2k)](https://github.com/abraham/twitteroauth) - A Twitter OAuth library.

### Markup and CSS

\*Libraries for working with markup and CSS formats.

*   [Cebe Markdown (⭐989)](https://github.com/cebe/markdown) - An fast and extensible Markdown parser.
*   [CommonMark PHP (⭐2.4k)](https://github.com/thephpleague/commonmark) - Highly-extensible Markdown parser which fully supports the [CommonMark spec](https://spec.commonmark.org/).
*   [Decoda (⭐196)](https://github.com/milesj/decoda) - A lightweight markup parser library.
*   [Essence (⭐765)](https://github.com/essence/essence) - A library for extracting web media.
*   [Embera (⭐305)](https://github.com/mpratt/Embera) - An Oembed consumer library.
*   [HTML to Markdown (⭐1.5k)](https://github.com/thephpleague/html-to-markdown) - Converts HTML into Markdown.
*   [HTML5 PHP (⭐1.1k)](https://github.com/Masterminds/html5-php) - An HTML5 parser and serializer library.
*   [Parsedown (⭐14k)](https://github.com/erusev/parsedown) - Another Markdown parser.
*   [PHP CSS Parser (⭐1.6k)](https://github.com/sabberworm/PHP-CSS-Parser) - A Parser for CSS Files written in PHP.
*   [PHP Markdown (⭐3.3k)](https://github.com/michelf/php-markdown) - A Markdown parser.
*   [Shiki PHP (⭐225)](https://github.com/spatie/shiki-php) - A [Shiki (⭐3.9k)](https://github.com/shikijs/shiki) code highlighting package in PHP.
*   [VObject (⭐527)](https://github.com/sabre-io/vobject) - A library for parsing VCard and iCalendar objects.

### JSON

*Libraries for working with JSON.*

*   [JSON Lint (⭐1.3k)](https://github.com/Seldaek/jsonlint) - A JSON lint utility.
*   [JSONMapper (⭐148)](https://github.com/JsonMapper/JsonMapper) - A library for mapping JSON to PHP objects.

### Strings

*Libraries for parsing and manipulating strings.*

*   [Agent (⭐4.1k)](https://github.com/jenssegers/agent) - A PHP desktop/mobile user agent parser, based on Mobiledetect.
*   [ANSI to HTML5 (⭐211)](https://github.com/sensiolabs/ansi-to-html) - An ANSI to HTML5 converter library.
*   [Color Jizz (⭐282)](https://github.com/mikeemoo/ColorJizz-PHP) - A library for manipulating and converting colours.
*   [Device Detector (⭐2.3k)](https://github.com/matomo-org/device-detector) - Another library for parsing user agent strings.
*   [Jieba-PHP (⭐1.2k)](https://github.com/fukuball/jieba-php) - A PHP port of Python's jieba. Chinese text segmentation for natural language processing.
*   [Mobile-Detect (⭐10k)](https://github.com/serbanghita/Mobile-Detect) - A lightweight PHP class for detecting mobile devices (including tablets).
*   [Patchwork UTF-8 (⭐80)](https://github.com/nicolas-grekas/Patchwork-UTF8) - A portable library for working with UTF-8 strings.
*   [Portable ASCII (⭐357)](https://github.com/voku/portable-ascii) - A library to convert strings to ascii.
*   [Portable UTF-8 (⭐471)](https://github.com/voku/portable-utf8) - A string manipulation library with UTF-8 safe replacement methods.
*   [Slugify (⭐2.8k)](https://github.com/cocur/slugify) - A library to convert strings to slugs.
*   [SQL Formatter (⭐3.9k)](https://github.com/jdorn/sql-formatter/) - A library for formatting SQL statements.
*   [Stringy (⭐140)](https://github.com/voku/Stringy) - A string manipulation library with multibyte support.
*   [UA Parser (⭐2k)](https://github.com/tobie/ua-parser/tree/master/php) - A library for parsing user agent strings.
*   [URLify (⭐660)](https://github.com/jbroadway/urlify) - A PHP port of Django's URLify.js.
*   [UUID (⭐12k)](https://github.com/ramsey/uuid) - A library for generating UUIDs.

### Numbers

*Libraries for working with numbers.*

*   [Brick\Math (⭐1.4k)](https://github.com/brick/math) - A library providing large number support: `BigInteger`, `BigDecimal` and `BigRational`.
*   [ByteUnits (⭐156)](https://github.com/gabrielelana/byte-units) - A library to parse, format and convert byte units in binary and metric systems.
*   [DecimalObject (⭐15)](https://github.com/spryker/decimal-object) - A value object to handle decimals/floats easily and more precisely.
*   [IP (⭐220)](https://github.com/darsyn/ip) - An immutable value object for working with IPv4 and IPv6 addresses.
*   [LibPhoneNumber for PHP (⭐4.2k)](https://github.com/giggsey/libphonenumber-for-php) - A PHP implementation of Google's phone number handling library.
*   [PHP Conversion (⭐126)](https://github.com/Crisu83/php-conversion) - Another library for converting between units of measure.
*   [PHP Units of Measure (⭐21)](https://github.com/triplepoint/php-units-of-measure) - A library for converting between units of measure.
*   [MathPHP (⭐2.1k)](https://github.com/markrogoyski/math-php) - A math library for PHP.

### Filtering and Validation

*Libraries for filtering and validating data.*

*   [Assert (⭐2.3k)](https://github.com/beberlei/assert) - A validation library with a rich set of assertions. Supports assertion chaining and lazy assertions.
*   [Aura.Filter (⭐151)](https://github.com/auraphp/Aura.Filter) - Provides tools to validate and sanitize objects and arrays.
*   [CakePHP Validation (⭐39)](https://github.com/cakephp/validation) - Another validation library.
*   [Filterus (⭐452)](https://github.com/ircmaxell/filterus) - A simple PHP filtering library.
*   [ISO-codes (⭐763)](https://github.com/ronanguilloux/IsoCodes) - A library for validating inputs according standards from ISO, International Finance, Public Administrations, GS1, Book Industry, Phone numbers & Zipcodes for many countries.
*   [JSON Schema (⭐3.3k)](https://github.com/justinrainbow/json-schema) - A [JSON Schema](https://json-schema.org/) validation library.
*   [MetaYaml (⭐100)](https://github.com/romaricdrigon/MetaYaml) - A schema validation library that supports YAML, JSON and XML.
*   [Respect Validation (⭐5.6k)](https://github.com/Respect/Validation) - A simple validation library.
*   [Upload (⭐1.7k)](https://github.com/brandonsavage/Upload) - A library for handling file uploads and validation.
*   [Valitron (⭐1.5k)](https://github.com/vlucas/valitron) - Another validation library.
*   [Volan (⭐43)](https://github.com/serkin/Volan) - Another simplified validation library.

### API

*Libraries and web tools for developing APIs.*

*   [API Platform](https://api-platform.com) - Expose in minutes an hypermedia REST API that embraces JSON-LD, Hydra format.
*   [Laminas API Tool Skeleton (⭐41)](https://github.com/laminas-api-tools/api-tools-skeleton) - An API builder built with the Laminas Framework.
*   [Drest (⭐87)](https://github.com/leedavis81/drest) - A library for exposing Doctrine entities as REST resource endpoints.
*   [HAL (⭐204)](https://github.com/blongden/hal) - A Hypertext Application Language (HAL) builder library.
*   [Hateoas (⭐996)](https://github.com/willdurand/Hateoas) - A HATEOAS REST web service library.
*   [Jane (⭐427)](https://github.com/janephp/janephp/) - An OpenApi client generator with validation support.
*   [Negotiation (⭐1.3k)](https://github.com/willdurand/Negotiation) - A content negotiation library.
*   [Restler (⭐1.4k)](https://github.com/Luracast/Restler) - A lightweight framework to expose PHP methods as RESTful web API.
*   [wsdl2phpgenerator (⭐803)](https://github.com/wsdl2phpgenerator/wsdl2phpgenerator) - A tool to generate PHP classes from SOAP WSDL files.

### Caching and Locking

*Libraries for caching data and acquiring locks.*

*   [APIx Cache (⭐110)](https://github.com/apix/cache) - A thin PSR-6 cache wrapper to various caching backends emphasising cache tagging and indexing.
*   [CacheTool (⭐1.4k)](https://github.com/gordalina/cachetool) - A tool to clear APC/opcode caches from the command line.
*   [CakePHP Cache (⭐49)](https://github.com/cakephp/cache) - A caching library.
*   [Doctrine Cache (⭐7.5k)](https://github.com/doctrine/cache) - A caching library.
*   [Metaphore (⭐102)](https://github.com/sobstel/metaphore) - Cache slam defense using a semaphore to prevent dogpile effect.
*   [Stash (⭐943)](https://github.com/tedious/Stash) - Another library for caching.
*   [Laminas Cache (⭐63)](https://github.com/laminas/laminas-cache) - Another caching library.
*   [Lock (⭐867)](https://github.com/php-lock/lock) - A lock library to provide exclusive execution.

### Data Structure and Storage

*Libraries that implement data structure or storage techniques.*

*   [CakePHP Collection (⭐84)](https://github.com/cakephp/collection) - A simple collections library.
*   [Fractal (⭐3.5k)](https://github.com/thephpleague/fractal) - A library for converting complex data structures to JSON output.
*   [Ginq (⭐190)](https://github.com/akanehara/ginq) - Another PHP library based on .NET's LINQ.
*   [JsonMapper (⭐1.4k)](https://github.com/cweiske/jsonmapper) - A library that maps nested JSON structures onto PHP classes.
*   [JSON Machine (⭐764)](https://github.com/halaxa/json-machine) - Provides iteration over huge JSONs using simple `foreach`
*   [Knapsack (⭐540)](https://github.com/DusanKasan/Knapsack) - Collection library inspired by Clojure's sequences.
*   [msgpack.php (⭐365)](https://github.com/rybakit/msgpack.php) - A pure PHP implementation of the [MessagePack](https://msgpack.org/) serialization format.
*   [PINQ (⭐466)](https://github.com/TimeToogo/Pinq) - A PHP library based on .NET's LINQ (Language Integrated Query).
*   [Serializer (⭐2.2k)](https://github.com/schmittjoh/serializer) - A library for serialising and de-serialising data.
*   [YaLinqo (⭐432)](https://github.com/Athari/YaLinqo) - Yet Another LINQ to Objects for PHP.
*   [Laminas Serializer (⭐27)](https://github.com/laminas/laminas-serializer) - Another library for serialising and de-serialising data.

### Notifications

*Libraries for working with notification software.*

*   [JoliNotif (⭐1.2k)](https://github.com/jolicode/JoliNotif) - A cross-platform library for desktop notification (support for Growl, notify-send, toaster, etc)
*   [Notification Pusher (⭐1.2k)](https://github.com/Ph3nol/NotificationPusher) - A standalone library for device push notifications.
*   [Notificato (⭐223)](https://github.com/mac-cain13/notificato) - A library for handling push notifications.
*   [Notificator (⭐188)](https://github.com/namshi/notificator) - A lightweight notification library.
*   [Php-pushwoosh (⭐63)](https://github.com/gomoob/php-pushwoosh) - A PHP Library to easily send push notifications with the Pushwoosh REST Web Services.

### Deployment

*Libraries for project deployment.*

*   [Deployer (⭐9.6k)](https://github.com/deployphp/deployer) - A deployment tool.
*   [Envoy (⭐1.5k)](https://github.com/laravel/envoy) - A tool to run SSH tasks with PHP.
*   [Rocketeer (⭐2.7k)](https://github.com/rocketeers/rocketeer) - A fast and easy deployer for the PHP world.

### Internationalisation and Localisation

*Libraries for Internationalization (I18n) and Localization (L10n).*

*   [Aura.Intl (⭐84)](https://github.com/auraphp/Aura.Intl) - Provides internationalization (I18N) tools, specifically package-oriented per-locale message translation.
*   [CakePHP I18n (⭐27)](https://github.com/cakephp/i18n) - Message translation and localization for dates and numbers.

### Serverless

*Libraries and tools to help build serverless web applications.*

*   [Bref](https://bref.sh/) - Serverless PHP on AWS Lambda.
*   [OpenWhisk](https://openwhisk.apache.org/) - An open-source serverless cloud platform.
*   [Serverless Framework](https://www.serverless.com/framework) - An open-source framework for building serverless applications.
*   [Laravel Vapor](https://vapor.laravel.com/) - A serverless deployment platform for Laravel, powered by AWS.

## Configuration

*Libraries and tools for configuration.*

*   [PHP Dotenv (⭐12k)](https://github.com/vlucas/phpdotenv) - Parse and load environment variables from `.env` files.
*   [Symfony Dotenv (⭐3.4k)](https://github.com/symfony/dotenv)- Parse and load environment variables from `.env` files.
*   [Yo! Symfony TOML (⭐173)](https://github.com/yosymfony/toml) - A PHP parser for [TOML (⭐18k)](https://github.com/toml-lang/toml).

### Third Party APIs

*Libraries for accessing third party APIs.*

*   [Amazon Web Service SDK (⭐5.7k)](https://github.com/aws/aws-sdk-php) - The official PHP AWS SDK library.
*   [AsyncAWS](https://async-aws.com/) - An unofficial asynchronous PHP AWS SDK.
*   [Campaign Monitor](https://campaignmonitor.github.io/createsend-php/) - The official Campaign Monitor PHP library.
*   [Github (⭐2k)](https://github.com/KnpLabs/php-github-api) - A library to interface with the Github API.
*   [Mailgun (⭐1k)](https://github.com/mailgun/mailgun-php) The official Mailgun PHP API.
*   [Square (⭐115)](https://github.com/square/connect-php-sdk) - The official Square PHP SDK for payments and other Square APIs.
*   [Stripe (⭐3.2k)](https://github.com/stripe/stripe-php) - The official Stripe PHP library.
*   [Twilio (⭐1.4k)](https://github.com/twilio/twilio-php) - The official Twilio PHP REST API.

### Extensions

*Libraries to help build PHP extensions.*

*   [PHP CPP](https://www.php-cpp.com/) - A C++ library for developing PHP extensions.
*   [Zephir (⭐3.2k)](https://github.com/zephir-lang/zephir) - A compiled language between PHP and C++ for developing PHP extensions.

### Miscellaneous

*Useful libraries or utilities that don't fit into the categories above.*

*   [Annotations (⭐6.5k)](https://github.com/doctrine/annotations) - An annotation library (part of Doctrine).
*   [BotMan (⭐5.7k)](https://github.com/botman/botman) - A framework agnostic PHP library to build cross-platform chat bots.
*   [ClassPreloader (⭐355)](https://github.com/ClassPreloader/ClassPreloader) - A library for optimising autoloading.
*   [Hprose-PHP (⭐2k)](https://github.com/hprose/hprose-php) - A cross-language RPC.
*   [noCAPTCHA (⭐339)](https://github.com/ARCANEDEV/noCAPTCHA) - Helper for Google's noCAPTCHA (reCAPTCHA).
*   [Pagerfanta (⭐1.6k)](https://github.com/whiteoctober/Pagerfanta) - A pagination library.
*   [Safe (⭐2.1k)](https://github.com/thecodingmachine/safe) - All PHP functions, rewritten to throw exceptions instead of returning false.
*   [SuperClosure (⭐1.7k)](https://github.com/jeremeamia/super_closure) - A library that allows Closures to be serialized.

# Software

*Software for creating a development environment.*

### PHP Installation

*Tools to help install and manage PHP on your computer.*

*   [Brew PHP Switcher (⭐856)](https://github.com/philcook/brew-php-switcher) - Brew PHP switcher.
*   [HomeBrew](https://brew.sh/) - A package manager for OSX.
*   [Laravel Valet](https://laravel.com/docs/master/valet) - A development environment for macOS.
*   [PHP Brew (⭐5k)](https://github.com/phpbrew/phpbrew) - A PHP version manager and installer.
*   [PHP Build (⭐949)](https://github.com/php-build/php-build) - Another PHP version installer.
*   [PHP OSX](https://php-osx.liip.ch/) - A PHP installer for OSX.

### Development Environment

*Software and tools for creating and sharing a development environment.*

*   [Ansible](https://www.ansible.com/) - A radically simple orchestration framework.
*   [Docker](https://www.docker.com/) - A containerization platform.
*   [Docker PHP Extension Installer (⭐2.6k)](https://github.com/mlocati/docker-php-extension-installer) - Easily install PHP extensions in Docker containers.
*   [Expose (⭐3.9k)](https://github.com/beyondcode/expose) - An open source PHP tunneling service.
*   [Lando](https://lando.dev/) - Push-button development environments.
*   [Laravel Homestead](https://laravel.com/docs/master/homestead) - A local development environment for Laravel.
*   [Laradock](http://laradock.io/) - A full PHP development environment based on Docker.
*   [Puppet](https://puppet.com/) - A server automation framework and application.
*   [Takeout (⭐1.4k)](https://github.com/tighten/takeout) - A Docker-based development-only dependency manager.
*   [Vagrant](https://www.vagrantup.com/) - A portable development environment utility.

### Virtual Machines

*Alternative PHP virtual machines.*

*   [Hack](https://hacklang.org/) - A programming language for HHVM.
*   [HHVM (⭐17k)](https://github.com/facebook/hhvm) - A Virtual Machine, Runtime and JIT for PHP by Facebook.
*   [PeachPie (⭐2.1k)](https://github.com/peachpiecompiler/peachpie) - PHP compiler and runtime for .NET and .NET Core.

### Text Editors and IDEs

*Text Editors and Integrated Development Environments (IDE) with support for PHP.*

*   [Eclipse for PHP Developers](https://www.eclipse.org/downloads/) - A PHP IDE based on the Eclipse platform.
*   [Apache NetBeans](https://netbeans.apache.org/) - An IDE with support for PHP and HTML5.
*   [PhpStorm](https://www.jetbrains.com/phpstorm/) - A commercial PHP IDE.
*   [VS Code](https://code.visualstudio.com/) - An open source code editor.

### Web Applications

*Web-based applications and tools.*

*   [3V4L](https://3v4l.org/) - An online PHP & HHVM shell.
*   [Adminer](https://www.adminer.org/) - Database management in a single PHP file.
*   [Cachet (⭐13k)](https://github.com/cachethq/cachet) - The open source status page system.
*   [DBV (⭐1.7k)](https://github.com/victorstanciu/dbv) - A database version control application.
*   [Lychee (⭐6.1k)](https://github.com/electerious/Lychee) - An easy to use and great looking photo-management-system.
*   [MailCatcher (⭐5.8k)](https://github.com/sj26/mailcatcher) - A web tool for capturing and viewing emails.
*   [phpMyAdmin (⭐6.2k)](https://github.com/phpmyadmin/phpmyadmin) - A web interface for MySQL/MariaDB.
*   [PHP Queue (⭐646)](https://github.com/CoderKungfu/php-queue) - An application for managing queueing backends.
*   [phpRedisAdmin (⭐2.9k)](https://github.com/ErikDubbelboer/phpRedisAdmin) - A simple web interface to manage [Redis](https://redis.io/) databases.
*   [PHPSandbox](https://phpsandbox.io) - An online IDE for PHP in the browser.

### Infrastructure

*Infrastructure for providing PHP applications and services.*

*   [appserver.io (⭐951)](https://github.com/appserver-io/appserver) - A multithreaded application server for PHP, written in PHP.
*   [php-pm (⭐6.4k)](https://github.com/php-pm/php-pm) - A process manager, supercharger and load balancer for PHP applications.
*   [RoadRunner (⭐6.8k)](https://github.com/roadrunner-server/roadrunner) - High-performance PHP application server, load-balancer and process manager.

# Resources

Various resources, such as books, websites and articles, for improving your PHP development skills and knowledge.

### PHP Websites

*Useful PHP-related websites.*

*   [libs.garden: PHP](https://libs.garden/php) - An overview of fastest growing PHP libraries.
*   [Nomad PHP](https://nomadphp.com/) - A online PHP learning resource.
*   [Laravel News](https://laravel-news.com/) - The official Laravel blog.
*   [PHP Annotated Monthly](https://blog.jetbrains.com/phpstorm/tag/php-annotated-monthly/) - A monthly digest of PHP news.
*   [PHP Best Practices](https://phpbestpractices.org/) - A PHP best practice guide.
*   [PHP FIG](https://www.php-fig.org/) - The PHP Framework Interoperability Group.
*   [PHP Package Development Standards](http://php-pds.com) - Package development standards for PHP.
*   [PHP School](https://www.phpschool.io/) - Open Source Learning for PHP.
*   [PHP Security](https://phpsecurity.readthedocs.io/en/latest/index.html) - A guide to PHP security.
*   [PHP The Right Way](https://phptherightway.com/) - A PHP best practice quick reference guide.
*   [PHP UG](https://php.ug) - A website to help people locate their nearest PHP user group (UG).
*   [PHP Versions](http://phpversions.info/) - Lists which versions of PHP are available on several popular web hosts.
*   [PHP Watch](https://php.watch/) - PHP articles, news, upcoming changes, RFCs and more.
*   [PHP Weekly](https://www.phpweekly.com/archive.html) - A weekly PHP newsletter.
*   [Seven PHP](https://7php.com/) - A website that interviews members of the PHP community.

### PHP Books

*Fantastic PHP-related books.*

*   [Domain-Driven Design in PHP](https://leanpub.com/ddd-in-php) - Real examples written in PHP showcasing DDD Architectural Styles.
*   [Functional Programming in PHP](https://www.functionalphp.com/) - This book will show you how to leverage these new PHP5.3+ features by understanding functional programming principles
*   [Grumpy PHPUnit](https://leanpub.com/grumpy-phpunit) - A book about unit testing with PHPUnit by Chris Hartjes.
*   [Mastering Object-Orientated PHP](https://www.brandonsavage.net/) - A book about object-orientated PHP by Brandon Savage.
*   [Modern PHP New Features and Good Practices](https://www.oreilly.com/library/view/\~/9781491905173/) - A book about new PHP features and best practices by Josh Lockhart.
*   [Modernizing Legacy Applications in PHP](https://leanpub.com/mlaphp) - A book about modernizing legacy PHP applications by Paul M. Jones.
*   [PHP 7 Upgrade Guide](https://leanpub.com/php7) - An ebook covering all of the features and changes in PHP 7 by Colin O'Dell.
*   [PHP Pandas](https://daylerees.com/php-pandas/) - A book about learning to write PHP by Dayle Rees.
*   [Scaling PHP Applications](https://www.scalingphpbook.com) - An ebook about scaling PHP applications by Steve Corona.
*   [Securing PHP: Core Concepts](https://leanpub.com/securingphp-coreconcepts) - A book about common security terms and practices for PHP by Chris Cornutt.
*   [Signaling PHP](https://leanpub.com/signalingphp) - A book about catching PCNTL signals in CLI scripts by Cal Evans.
*   [The Grumpy Programmer's Guide to Building Testable PHP Applications](https://leanpub.com/grumpy-testing) - A book about building testing PHP applications by Chris Hartjes.
*   [XML Parsing with PHP](https://www.phparch.com/books/xml-parsing-with-php/) - This book covers parsing and validating XML documents, leveraging XPath expressions, and working with namespaces as well as how to create and modify XML files programmatically.

### PHP Videos

*Fantastic PHP-related videos.*

*   [Nomad PHP Lightning Talks](https://www.youtube.com/c/nomadphp) - 10 to 15 minute Lightning Talks by PHP community members.
*   [PHP UK Conference](https://www.youtube.com/user/phpukconference/videos) - A collection of videos from the PHP UK Conference.
*   [Programming with Anthony](https://www.youtube.com/playlist?list=PLM-218uGSX3DQ3KsB5NJnuOqPqc5CW2kW) - A video series by Anthony Ferrara.
*   [Taking PHP Seriously](https://www.infoq.com/presentations/php-history/) - A talk outlining PHP's strengths by Keith Adams of Facebook.
*   [Laracasts](https://laracasts.com) - Screencasts about Laravel, Vue JS and more.
*   [Laravel YouTube Channel](https://www.youtube.com/channel/UCfO2GiQwb-cwJTb1CuRSkwg) - The official Laravel YouTube channel.
*   [SymfonyCasts](https://symfonycasts.com/) - Screencasts and tutorials about PHP and Symfony.

### PHP Podcasts

*Podcasts with a focus on PHP topics.*

*   [Laravel Podcast](https://laravelpodcast.com/) - Laravel and PHP development news and discussion.
*   [PHP Internals News](https://phpinternals.news) - A podcast about PHP internals.
*   [PHP Roundtable](https://phproundtable.com/) - The PHP Roundtable is a casual gathering of developers discussing topics that PHP nerds care about.
*   [PHP Town Hall](https://phptownhall.com/) - A casual PHP podcast by Ben Edmunds and Phil Sturgeon.
*   [Voices of the ElePHPant](https://voicesoftheelephpant.com/) Interviews with the people that make the PHP community special.

### PHP Newsletters

*PHP-related news directly to your inbox.*

*   [PHP Weekly](https://www.phpweekly.com/) - A weekly newsletter about PHP.

### PHP Reading

*PHP-related reading materials.*

*   [php\[architect\]](https://www.phparch.com/magazine/) - A monthly magazine dedicated to PHP.

### PHP Internals Reading

*Reading materials related to the PHP internals or performance.*

*   [PHP RFCs](https://wiki.php.net/rfc) - The home of PHP RFCs (Request for Comments).
*   [Externals](https://externals.io/) - PHP internal discussions.
*   [PHP RFC Watch](https://php-rfc-watch.beberlei.de/) - Watch the latest PHP [RFCs](https://wiki.php.net/rfc).
*   [PHP Internals Book](https://www.phpinternalsbook.com/) - An online book about PHP internals, written by three core developers.

