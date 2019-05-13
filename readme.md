## Code Setup
- Clone Project from [GIT](https://github.com/gaurang-joshi/test "GIT")
- Go to that directory in terminal `cd /var/www/test`
- Create MySQL database with name "techflake"
- Run command `php artisan migrate` to create tables
- Run Seeder for 50000 user insertation by `php artisan db:seed` (It's huge data so, you have to wait for probabbly an hour)
- Then, create virtual host as `http://techflake.local`
- Now, just open local virtual host and test the code.
