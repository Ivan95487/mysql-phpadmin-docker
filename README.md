# MySQL + phpMyAdmin with Docker

## About
This project runs MySQL and phpMyAdmin using Docker Compose.

## Services
- MySQL database: port 3306
- phpMyAdmin web interface: http://localhost:8081

## Requirements
- Docker Desktop
- Docker Compose

## How to run
1. Create a `.env` file.
2. Set your MySQL password in `.env`:

   MYSQL_ROOT_PASSWORD=YourPassword

3. Open PowerShell in this folder.
4. Run:

   docker compose up -d

## How to stop

    docker compose down