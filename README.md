# Task Manager

A simple Task Management application built using **Ruby on Rails**. It allows users to create, view, update, and delete tasks.

## Tech Stack

- Ruby 3.4.12
- Ruby on Rails 8.1.4
- SQLite3
- HTML, CSS, JavaScript
- Puma Web Server

## Features

- Create new tasks
- View all tasks
- View individual task details
- Edit existing tasks
- Delete tasks
- Manage task status

## Getting Started

### 1. Clone the Repository

```bash
git clone <repository-url>
cd task_manager
```

### 2. Install Dependencies

```bash
bundle install
```

### 3. Set Up the Database

```bash
bin/rails db:create
bin/rails db:migrate
```

### 4. Start the Rails Server

```bash
bin/rails server
```

Open your browser and visit:

```text
http://localhost:3000/tasks
```

## Useful Commands

```bash
# Start Rails server
bin/rails server

# Run database migrations
bin/rails db:migrate

# Check available routes
bin/rails routes

# Run tests
bin/rails test
```

## Project Structure

- `app/models` – Database models
- `app/controllers` – Application controllers
- `app/views` – User interface and templates
- `config/routes.rb` – Application routes
- `db/migrate` – Database migrations

## License

This project is created for learning and practice purposes.
