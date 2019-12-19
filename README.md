# Laravel Realtime Notification
This is demo application for real time notification.

<h3>Init Commands</h3>

`composer install`

`npm install`

Setup database configuration into the `.env`. if you have not `.env` file the please copy from `.env.example` to `.env`.

<h3>Run Server</h3>

`php artisan serve`

`php artisan websocket:serve`

After run successfully server call route `/laravel-websockets` for realtime statistics.

Run Home URL: `127.0.0.1:8000` for display realtime notification.

User send new notification from this URL: `127.0.0.1:8000/user/{username}`. when user call this URL with username parameter from url then display home URL notification Icon with message.



## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

Thanks, and let me know if you have any queries.