# Task Manager App

This is a simple Task Management web app built using:

- Next.js (frontend)
- Supabase (backend and database)

## Features

- User login and signup
- Role-based access (admin, user)
- Add, edit, delete tasks
- User profile page
- Notifications (real-time)
- Clean and modern layout

## How to Set Up

### 1. Clone the project

```bash
git clone https://github.com/chzeeshansaleem/nextJS_supabase_project.git
cd nextJS_supabase_project
```
# Install required packages
npm install

# Set up environment variables
Create a file named .env.local and add this:

NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key

Replace your_supabase_url and your_supabase_anon_key with your actual Supabase project values.

# Start the development server
npm run dev
Visit http://localhost:3000 to open the app in your browser.

# Folder Structure
``` 
components/        → Reusable UI components
pages/             → Routes like /login, /tasks
lib/               → Supabase client and auth helpers
services/          → Functions for tasks, auth, profile
styles/            → CSS or Tailwind styling
public/            → Static files (images, icons)

```

# Author
```
Zeeshan Saleem
Email: chzeeshan1322@gmail.com
```