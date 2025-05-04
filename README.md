# Salat Tracker

## Backend Setup
- `composer install`
- Copy `.env.example` to `.env` and set your DB credentials
- `php artisan migrate --seed`
- `php artisan serve`

_Hijri Conversion:_ uses `ummalqura-calendar` package; config in `config/hijri.php`

## Frontend Setup
- `pnpm install`
- Copy `.env.example` and set `VITE_API_URL`
- `pnpm dev`

Navigable routes:
- `/day/YYYY-MM-DD` → Daily tracker
- `/dashboard`      → Statistics dashboard
