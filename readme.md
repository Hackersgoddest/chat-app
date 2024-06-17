# feathers-chat

> A Feathers chat application

## About

This project uses [Feathers](http://feathersjs.com). An open source framework for building APIs and real-time applications.

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
