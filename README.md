
## Developing

**Getting Started**

*Clone this repo:*


*Enter the project folder:*

```
cd Students-Attendance-System-V1
```

*Install php dependencies:*

```
composer install
```

*Copy the env.example file to .env and generate new key:*

```
cp .env.example .env

php artisan key:generate
```

*Open to the .env file and change the database credentials to your database:*

*Migrate the database and the seeds:*

```
php artisan migrate:fresh --seed
```

**Workflow**

*Serve the project:*

```
php artisan serve
```

*Login and access project* 

Use the default email : **admin@app.com** and password : **password**

