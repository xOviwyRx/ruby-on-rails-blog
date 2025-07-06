# Ruby on Rails Blog

A simple blog application built with Ruby on Rails and SQLite.

## Features

- Create, read, update, and delete blog posts
- SQLite database integration
- RESTful routing
- Responsive design

## Tech Stack

- Ruby on Rails
- SQLite3
- HTML/CSS/ERB

## Setup

```bash
git clone https://github.com/xOviwyRx/ruby-on-rails-blog.git
cd ruby-on-rails-blog
bundle install
rails db:migrate
rails server
```

Visit `http://localhost:3000`

## Usage

- Browse articles at `/articles`
- Create new articles with the "New Article" button
- Edit or delete existing articles

## Database

Uses SQLite3 with an articles table containing:

- Title
- Body
- Timestamps

## Routes

`GET /articles` - List articles

`GET /articles/:id` - Show article

`POST /articles` - Create article

`PATCH /articles/:id` - Update article

`DELETE /articles/:id` - Delete article
