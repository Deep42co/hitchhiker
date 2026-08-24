# Hitchhiker

**Don't Panic.**

A Laravel installer from [Deep42](https://deep42.co). Pack a towel. Point people at `/install`. When `storage/installed` shows up, the universe is ready. The answer is still 42.

```bash
composer config repositories.hitchhiker vcs https://github.com/Deep42co/hitchhiker.git
composer require deep42/hitchhiker
php artisan vendor:publish --tag=installer-config
```

PHP 8.2+ · Laravel 10–13 · Livewire 3/4 · MIT

So long, and thanks for all the fish.
