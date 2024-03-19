## Project Structure

The project follows a typical MERN stack structure, with separate directories for client-side and server-side code:

- `client`: Contains the frontend code, built using React.
- `config`: Configuration files for the project.
- `controllers`: Controllers for handling business logic.
- `helpers`: Helper functions and utilities.
- `middlewares`: Custom middleware functions.
- `models`: Database models.
- `routes`: API routes.
- `server.js`: Entry point for the server.
- `.gitignore`: Specifies intentionally untracked files to ignore.
- `package.json` and `package-lock.json`: Dependency files for npm packages.

## Setting up Environment Variables

To set up environment variables for the project, follow these steps:

1. **Create a `.env` file**: In the root directory of the project, create a file named `.env`.

2. **Add Environment Variables**: Inside the `.env` file, add the following environment variables along with their corresponding values:

    ```
    MONGO_URL=
    JWT_SECRET=
    BRAINTREE_MERCHANT_ID=
    BRAINTREE_PUBLIC_KEY=
    BRAINTREE_PRIVATE_KEY=
    ```

3. **Save the `.env` file**: Make sure to save the `.env` file with the environment variables.

## Running the Project

To run the project, follow these steps:

1. **Install Dependencies**: Navigate to the root directory of the project and run the following command to install dependencies for both the client and server:

    ```
    npm install
    ```

2. **Start the Server**: Run the following command to start the server:

    ```
    node server.js
    ```

3. **Start the Client**: Navigate to the `client` directory and run the following command to start the React development server:

    ```
    npm start
    ```

4. **Access the Application**: Once the server and client are running, you can access the application by navigating to `http://localhost:3000` in your web browser.


