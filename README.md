# URL Shortener Service

A Python microservice built with Flask that shortens URLs using base62 encoding and stores them in a database.

## Features
- Shorten long URLs with a unique slug
- Redirect to original URL when slug is accessed
- Track number of clicks (optional)
- Admin panel to manage shortened URLs (optional)

## Tech Stack
- Python
- Flask
- SQLite / PostgreSQL
- Base62 encoding
- REST APIs

## How It Works
- POST `/shorten` → returns shortened URL
- GET `/slug` → redirects to original URL

## Example
