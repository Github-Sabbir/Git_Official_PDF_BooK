git config --global user.name "Github-Sabbir"
git config --global user.email mdabdulalimsabbir000@gmail.com
=========================================================================
git init
git add .
git commit -m "commit done"
git branch -M main
git remote add origin https://github.com/Github-Sabbir/REPONAME.git
git push -u origin main
=========================================================================
or push an existing repository from the command line
=========================================================================
git remote add origin https://github.com/Github-Sabbir/Eshopper.git
git branch -M main
git push -u origin main
=========================================================================
change kore ja kora lage
=========================================================================
git add README.md
git commit -m "ki change hoyeche seita bapare"
git push
=========================================================================
git add .
git commit -m "ki change hoyeche seita bapare"
git push
=========================================================================
Laravel project github theke download kore run kora
=========================================================================
git clone https://github.com/Github-Sabbir/ecommerce_furni.git
composer install --optimize-autoloader --no-dev

(Now copy .env.example file and make rename .env)
(Go to .env and change database connection to your database)
php artisan key:generate
php artisan migrate
(if ask for create database then write in the terminal (yes) )
npm install