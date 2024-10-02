Contact Us From Package
#This will send email to admin and save to contact query on database



<h1 align="center">
Banking System
</h1>



## Banking System
Implement a banking system with two types of users: Individual and Business. The system should
support deposit and withdrawal operations for both types of users.



How to setup locally

-  Clone the repository
```bash
git clone https://github.com/developeralamin/mediusware_task
```

- Install dependencies
```bash
composer install
```

- Create a copy of your .env file
```
cp .env.example .env
```

- Generate an app encryption key
```bash
php artisan key:generate
```

- Create Database Name .env file
```
DB_DATABASE = 
```
- Run migrations
```bash
php artisan migrate
```




- Run the local development server
```bash
php artisan serve
```

- Visit http://localhost:8000 in your browser
- Create account
- Login with email and password
