# Gigavel

A small Laravel-style PHP MVC framework. Models, views, controllers, routing, and enough structure to ship without pulling in a full Laravel stack. HTMX and Alpine.js handle interactive UI with little custom JavaScript.

## Stack

PHP (MVC), HTMX, Alpine.js, Composer

## Layout

```
gigavel/
├── app/Controllers/
├── config/routes.php
├── resources/views/
├── public/index.php
├── .env.example
└── composer.json
```

## Setup

```bash
composer install
cp .env.example .env
# point your web root (or `php -S`) at public/
```

## Why it exists

I wanted Laravel-shaped habits (routing, controllers, views) in a codebase I could read end to end. Gigavel is that middle ground.

## Author

Biruk Endrias — [iambiruk.vercel.app](https://iambiruk.vercel.app)
