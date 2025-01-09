# Flask App with MySQL Docker Setup

This is a simple Flask app that interacts with a MySQL database. The app allows users to submit messages, which are then stored in the database and displayed on the frontend.

## Usage

1. Start the containers using Docker Compose:

   ```bash
   docker-compose up --build
   ```

2. Interact with the app:

   - Visit http://localhost to see the frontend. You can submit new messages using the form.
   - Visit http://localhost:5000/insert_sql to insert a message directly into the `messages` table via an SQL query.

## Cleaning Up

To stop and remove the Docker containers, press `Ctrl+C` in the terminal where the containers are running, or use the following command:

```bash
docker-compose down
```
