# Simple To-Do App with Next.js & Supabase

This project is a simple To-Do application built using the Next.js framework for the frontend and Supabase as the backend. It's designed as a beginner-friendly introduction to full-stack development, providing hands-on experience with modern web technologies.

**Note:** This project was originally developed as workshop material for a Supabase workshop held on April 14, 2024.

## Why Next.js and Supabase?

This tech stack offers a fantastic learning experience due to the abundance of resources and the powerful features each technology provides:

### Next.js

While it might seem like a lot for a basic app, Next.js offers significant advantages, especially for learners:

* **The React Framework:** Built on top of React, the most popular frontend library, learning Next.js equips you with in-demand skills and opens up numerous opportunities in the tech industry. The extensive React and Next.js ecosystem ensures ample community support and learning resources.
* **Full-Stack Capabilities:** Next.js allows you to explore both frontend and backend concepts within a single framework. Features like Route Handlers and Middleware introduce you to essential backend concepts such as APIs and server-side logic.

### Supabase

Supabase is an open-source Backend as a Service (BaaS) and a robust alternative to Firebase.

* **Robust Database:** Supabase utilizes PostgreSQL, a highly reliable relational database. Beyond the database, it offers a comprehensive suite of features including Storage, Authentication, Edge Functions, Realtime subscriptions, and even Vector Embeddings, providing everything you need to build modern applications efficiently.
* **Exceptional Developer Experience:** Supabase boasts intuitive and user-friendly documentation, making it easy for developers of all experience levels to leverage its full potential and enjoy the learning process.

## Features

This simple To-Do app includes basic functionalities such as:

* Adding new tasks to the to-do list.
* Viewing the list of existing tasks.
* Marking tasks as completed.
* Deleting tasks from the list.

## Getting Started

To get started with this project, you will need to have Node.js and npm (or yarn) installed on your machine.

1.  **Clone the repository:**
    ```bash
    git clone [repository_url_here]
    cd [project_directory_name]
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```

3.  **Set up Supabase:**
    * Create a new project on the [Supabase website](https://supabase.com/).
    * Obtain your Supabase API URL and public API key from your project settings.
    * Create a `.env.local` file in the root of your project and add your Supabase credentials:
        ```
        NEXT_PUBLIC_SUPABASE_URL=YOUR_SUPABASE_URL
        NEXT_PUBLIC_SUPABASE_ANON_KEY=YOUR_SUPABASE_ANON_KEY
        ```
       
4.  **Run the development server:**
    ```bash
    npm run dev
    # or
    yarn dev
    ```

    Open your browser and navigate to `http://localhost:3000` to see the application running.

## Further Learning

This simple project is just the beginning! Here are some ideas for expanding your knowledge and the application:

* Explore more advanced Next.js features like dynamic routes and API routes.
* Dive deeper into Supabase features like user authentication and real-time database updates.
* Implement more complex UI elements and styling.
* Add unit and integration tests.

