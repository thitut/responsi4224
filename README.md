//tutorial install

composer install
npm install && npm run dev
php artisan key:generate
php artisan migrate --seed