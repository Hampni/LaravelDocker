1. Go to directory `/LaravelDocker`
2. Run command `git clone https://github.com/Hampni/laravelRegistrationForm`
3. Run `docker-compose up --build`
4. Go to `172.18.0.1:6080` and create Database named laravelRegistrationForm. User = `root`, Password = `2481632`
5. Create same `/laravelRegistrationForm/.env` file by example
6. Run command `docker-compose exec web bash`
7. Run this command to fill database with tables - php artisan migrate
8. Run this command to create some test data - php artisan db:seed
9. Run this command to make country picker working - php artisan db:seed CountriesSeeder
10. For authorisation to admin panel. Email: `admin@gmail.com` Password: `248163264`