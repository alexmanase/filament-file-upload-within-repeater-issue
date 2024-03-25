## How to run locally

```
git clone https://github.com/alexmanase/filament-file-upload-within-repeater-issue
composer install
php artisan key:generate
cp .env.example .env
touch database/database.sqlite
php artisan migrate:fresh --seed
```
