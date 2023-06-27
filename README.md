# FullStack Typescript App

This repository contains a full stack application built with Typescript. The repository is a monorepo and includes both the backend and frontend services.

## Overview

- `backend`: This directory contains the backend service written in TypeScript with Fastify.
- `frontend`: This directory contains the frontend service written in TypeScript with React.

## Getting Started

### Prerequisites

- Docker and Docker Compose installed on your machine.

### Setup

1. Clone the repository:

   ```
   git clone https://github.com/Baromeg/fullstack_AI.git
   ```

2. Navigate into the cloned repository:

```
cd full-stack-typescript-app
```

3. Build and run the Docker containers for the backend and frontend:

```
docker-compose up
```

> This command will start both services. The frontend will be available at `http://localhost:3000` and the backend at `http://localhost:8080`.

### Environment Variables

To run this project, you will need to add the following environment variables to your `secrets.env` file in the `backend` directory `backend/src/config`:

OPEN_API_KEY=variable_value

Replace OPEN_API_KEY=variable_value with your actual openAI API Key.

## Collaborators

- **Baltasar Romero** ([@Baromeg](https://github.com/Baromeg))
- **Fuad Ahmad Jamali** ([@fuadjamali](https://github.com/fuadjamali))
- **Kostiantyn Matvieienkov** ([@kostiantynn](https://github.com/kostiantynn))
- **Biruk D** ([@birukdwy](https://github.com/birukdwy))

### Contributing

Contributions are always welcome!

### License

ISC
