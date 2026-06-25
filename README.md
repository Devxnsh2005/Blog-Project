# Blog Project

A full stack blogging application where users can sign up, sign in, create blogs, update blogs, and read published blog posts. The project is built with a modern TypeScript based stack and follows a clean separation between frontend, backend, and shared validation logic.

## Tech Stack

### Frontend

* React
* TypeScript
* Vite
* Tailwind CSS
* React Router DOM
* Axios

### Backend

* Hono
* Cloudflare Workers
* Prisma
* Prisma Accelerate
* PostgreSQL
* JWT Authentication
* Wrangler

### Common Package

* Zod
* Shared validation schemas
* Shared TypeScript types

## Features

* User signup and signin
* JWT based authentication
* Protected blog routes
* Create blog posts
* Update blog posts
* View all blogs
* View individual blog details
* Shared input validation using Zod
* Separate frontend, backend, and common package structure

## Project Structure

```bash
Blog-Project
├── backend
│   ├── src
│   │   ├── index.ts
│   │   └── routes
│   │       ├── user.ts
│   │       └── blog.ts
│   ├── prisma
│   ├── package.json
│   └── wrangler.toml
│
├── common
│   ├── src
│   │   └── index.ts
│   └── package.json
│
└── frontend
    ├── src
    ├── package.json
    └── vite.config.ts
```
## Author

Devansh Gupta
