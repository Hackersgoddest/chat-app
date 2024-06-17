# feathers-chat

> A Feathers chat application

## About

This project uses [Feathers](http://feathersjs.com). An open source framework for building APIs and real-time applications.

## Table of Contents

- [Getting Started](#getting-started)
- [Usage](#usage)
- [Testing](#testing)
- [Scaffolding](#scaffolding)
- [Help](#help)
- [Contributing](#contributing)
- [Images](#images)



## Getting Started

1. Make sure you have [NodeJS](https://nodejs.org/), [yarn](https://classic.yarnpkg.com/en/docs/install#mac-stable) and [postgresql](https://www.postgresql.org/) installed.

2. Clone the repository to your local machine:

   ```sh
   git clone https://github.com/Hackersgoddest/chat-app.git
   ```

3. Install your dependencies

    ```
    cd path/to/feathers-chat
    yarn
    ```

4. Configure the environment variables:

    - Create a `.env` file in the `root` directory and set your Feathers secret key and database connection details:
         ```sh
        PORT=3000
        HOSTNAME=localhost
        DB_CONNECTION_STRING=postgres://username:password@localhost:5432/database-name
        FEATHERS_SECRET=secret-key

5. Start your app

    ```
    yarn compile # Compile TypeScript source
    yarn migrate # Run migrations to set up the database
    yarn dev
    ```

## Usage

Working on this Feathers chat application provides valuable learning experiences across various aspects of web development and software engineering. Here are some key lessons you can learn:

### 1. Setting Up a Modern Web Application
   - Dependency Management: Learn how to manage dependencies using Yarn.
   - Environment Configuration: Understand the importance of environment variables for configuring your application securely and flexibly.

### 2. Using FeathersJS
   - API Development: Gain hands-on experience in building RESTful and real-time APIs using FeathersJS.
   - Service Architecture: Learn how to structure your application with services, making it modular and easy to maintain.

### 3. Database Integration
   - PostgreSQL Setup: Learn how to configure and connect to a PostgreSQL database.
   - Migrations: Understand how to use database migrations to version and manage your database schema changes.

### 4. TypeScript in Node.js
   - TypeScript Compilation: Learn how to compile TypeScript code to JavaScript using a build process.
   - Type Safety: Experience the benefits of using TypeScript for type safety and improved code quality.

### 5. Real-Time Communication
   - WebSockets: Understand how real-time communication is implemented using WebSockets, enabling features like live chat.

### 6. User Authentication
   - Authentication: Implement user authentication, including sign-up and login functionalities, and learn how to manage user sessions securely.


## Testing

Run `yarn test` and all your tests in the `test/` directory will be run.

## Scaffolding

This app comes with a powerful command line interface for Feathers. Here are a few things it can do:

```
$ npx feathers help                           # Show all commands
$ npx feathers generate service               # Generate a new Service
```

## Help

For more information on all the things you can do with Feathers visit [docs.feathersjs.com](http://docs.feathersjs.com).

## Contributing
- Contributions to this project are welcome! If you have ideas for improvements or bug fixes, please submit an issue or a pull request.

## Images
![Sign In/Up Page](login.png)
![Chat Page](chat.png)
