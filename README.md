# Gigavel

A small Laravel-style PHP MVC framework. Routing, controllers, views, and enough structure to ship without a full Laravel install. HTMX and Alpine.js cover interactive UI with little custom JavaScript.

## When to use it

Teaching MVC, prototypes, and admin tools where Laravel would be heavier than the job.

## Stack

PHP, Composer, HTMX, Alpine.js

## Quick start

```bash
composer install
cp .env.example .env   # if present
php -S localhost:8080 -t public
# or point Nginx/Apache at public/
```

## Layout

```
app/Controllers/
config/
resources/views/
public/
```

## Status

Public build. Docs and examples improve in the open under IAMBIRUK.

## Author

Biruk Endrias — https://iambiruk.vercel.app · https://github.com/biruktk/Gigavel
