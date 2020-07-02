# Install

-------------------------------
1. download file, boleh ganti nama foldernya jadi "bebas"
2. run "composer install" in "bebas" pake terminal di dalam folder "bebas"
3. Bikin database dengan nama "db-bebas"
3. copy .env.example to .env and edit namanya jadi "db-bebas" sama hapus passwordnya
4. run "php artisan key:generate" di terminal 
5. run "php artisan migrate:refresh --seed" di terminal
6. chmod -R 777 storage di terminal 
7. run "php artisan serve" di terminal

