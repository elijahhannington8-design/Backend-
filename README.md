# Vercel & Express Backend

This project is a simple backend setup that can be run locally using Express or deployed as Serverless Functions on Vercel.

## Project Structure

- `api/hello.js`: Vercel Serverless Function.
- `server.js`: Express server for local development.
- `vercel.json`: Configuration for Vercel deployment.
- `package.json`: Project dependencies and scripts.

## Local Development

To run the server locally:

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the Express server:
   ```bash
   npm start
   ```

3. The server will be running at `http://localhost:5000`.
   - Root endpoint: `http://localhost:5000/`
   - Hello endpoint: `http://localhost:5000/api/hello`

## Deployment

This project is configured for deployment on Vercel. Vercel will automatically detect the `api/` directory and deploy the functions within it.
