# Login Page

A simple static login page served via Docker using Nginx.

## Prerequisites

- Docker installed on your system.

## Usage

1. Build the Docker image:
   ```
   docker build -t login-page .
   ```

2. Run the container:
   ```
   docker run -p 8080:80 login-page
   ```

3. Open your browser and navigate to `http://localhost:8080` to view the login page.

## Files

- `index.html`: The login page HTML with basic styling.
- `Dockerfile`: Configuration to build the Docker image using Nginx.

## Troubleshooting

- If port 8080 is already in use, change the port mapping in the `docker run` command (e.g., `-p 8081:80`).
- Ensure Docker is running before executing the commands.