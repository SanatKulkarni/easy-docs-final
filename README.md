# Easy-Docs: A Collaborative Document Workspace


Easy-Docs is a modern, collaborative document workspace built with the latest web technologies. It's designed to help you create, organize, and share your ideas and documents seamlessly.

# QR Code To Try it Yourself
![easydocsqr](https://github.com/user-attachments/assets/8bb7a6dc-3739-45b0-a00b-495bda86e219)



## Demo

[![Easy-Docs Demo](https://img.youtube.com/vi/TGHms-kE4Mg/0.jpg)](https://www.youtube.com/watch?v=TGHms-kE4Mg)

**[Watch the Demo on YouTube](https://www.youtube.com/watch?v=TGHms-kE4Mg)**

## Features

*   **Real-time Collaboration:** Work on documents with your team simultaneously.
*   **Intuitive Interface:**  Easy-to-use document creation and organization.
*   **Rich Text Editing:**  Format your documents with headings, lists, images, and more.
*   **Customizable Themes:** Switch between light and dark themes.
*   **Secure Authentication:**  Powered by Clerk for secure user management.
*   **Database Persistence:**  Utilizes Drizzle ORM and Neon DB for reliable data storage.
*   **Modern Tech Stack:** Built with the latest and greatest web development technologies.

## Tech Stack

*   **Frontend:**
    *   [Next.js](https://nextjs.org/): A React framework for building performant and scalable web applications.
*   **Backend:**
    *   [Node.js](https://nodejs.org/en/):  A JavaScript runtime for server-side development.
*   **Authentication:**
    *   [Clerk](https://clerk.com/):  Complete user management with authentication and authorization.
*   **ORM (Object-Relational Mapper):**
    *   [Drizzle ORM](https://orm.drizzle.team/): A TypeScript ORM designed for ease of use and type safety.
*   **Database:**
    *   [Neon DB](https://neon.tech/): A fully managed Serverless PostgreSQL with a generous free tier.

## Getting Started

1.  **Clone the Repository:**

    ```bash
    git clone https://github.com/SanatKulkarni/easy-docs-final/
    cd easy-docs
    ```

2.  **Install Dependencies:**

    ```bash
    npm install  # or yarn install or pnpm install
    ```

3.  **Configure Environment Variables:**

    *   Create a `.env.local` file in the root directory.
    *   Add the following environment variables (replace with your actual values):

        ```
        DATABASE_URL=<your_neon_db_connection_string>
        NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<your_clerk_publishable_key>
        CLERK_SECRET_KEY=<your_clerk_secret_key>
        NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
        NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
        ```

    *   You can obtain these credentials from the [Neon](https://neon.tech/) and [Clerk](https://clerk.com/) dashboards after setting up accounts and projects.

4.  **Run Migrations:**

    ```bash
    # Follow Drizzle ORM's migration instructions specific to your project setup.
    # This is just a placeholder, make sure to follow the correct steps
    # based on your Drizzle ORM configuration.

    #Example command
    #npx drizzle-kit generate:pg
    #npx drizzle-kit push:pg

    ```

5.  **Start the Development Server:**

    ```bash
    npm run dev  # or yarn dev or pnpm dev
    ```

    Open your browser and navigate to `http://localhost:3000`.

## Created By

[Sanat Kulkarni](https://github.com/SanatKulkarni) 
