# Web Application Exercise

A little exercise to build a web application following an agile development process. See the [instructions](instructions.md) for more detail.

## Product Vision Statement

A minimalist and intuitive to-do list app designed for simple and quick task management.

## User stories

- As a student, I want to sign up so I can track my to-do.
- As a developer, I want to edit so I can be flexible with my to-do.
- As a professor, I want to delete so I can remove to-dos that are no longer relevant.
- As an enterpreneur, I want to finish so I can list my to-do as done and feel good about it.
- As a busy CEO, I want to search so I can remember my to-do.
- As a writer, I want to see a display of my to-do so I can visualize my progress.
- As a non-tech savvy user, I want a simple interface so I can easily use the app.
- As a teacher, I want to prioritize tasks, so I can focus on the most important ones first.

## Steps necessary to run the software

### Prerequisites

- Docker and Docker Compose installed on your system

### Setup and Run

Make sure [docker](https://www.docker.com/) is installed on your machine

1. Clone this repository:

   ```
   git clone https://github.com/software-students-spring2025/2-web-app-bytebuddies.git
   cd 2-web-app-bytebuddies
   ```

2. Create a `.env` file based on the `.env.example` template:

   ```
   cp .env.example .env
   ```

3. Start the application with Docker Compose:

   ```
   docker-compose up -d
   ```

4. Access the application in your browser at:

   ```
   http://localhost:8000
   ```

5. To stop the application:

   ```
   docker-compose down
   ```

6. To stop the application and remove volumes:

   ```
   docker-compose down -v
   ```

## Task boards

<https://github.com/orgs/software-students-spring2025/projects/30>
