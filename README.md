# Laravel Reverb Chat

Laravel Reverb Chat is a chat application that uses Laravel Reverb to provide real-time functionality.

## System Requirements

| PHP | NodeJS | Composer |
| :-: | :----: | :------: |
| 8.2 |  20.x  |   2.x    |

## Project Setup

### Copy the environment configuration file

```bash
cp .env.example .env
```

### Install dependencies

```bash
composer install
npm install
```
### Generate the application key

```bash
php artisan key:generate
```

### Run database migrations

```bash
php artisan migrate
```

## Start the Application

### Start the Laravel backend

```bash
php artisan serve
```

### Start the frontend

```bash
npm run dev:tailwind
```

### Run Laravel Reverb

```bash
php artisan reverb:start
```

## Access the Application

After completing the steps above, you can access the application through your browser at:

-   Web `http://localhost:8000`
