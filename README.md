# Tasks for Today Management System

A four-page task management system built with CodeIgniter 4 and MySQL.

## Pages

- `/` — shows only today's tasks using the Asia/Manila date
- `/tasks` — shows all tasks ordered by date
- `/profile` — shows one demo user
- `/about` — identifies the developer

## Local setup

1. Install dependencies with `composer install`.
2. Create a `.env` file from the project's `env` file.
3. Set `app.baseURL` and the MySQL connection settings in `.env`.
4. Import `database/tasks_today.sql` into MySQL **once**.
5. Run `php spark serve --port 8082`.
6. Visit `http://localhost:8082/`.

The SQL file creates the `tasks_today` database with 8 sample tasks
and 1 demo user.