
# Eco-Powered AI Microservice Challenge

## Introduction

In this challenge, you will design and develop a microservice that merges AI-driven technology with an eco-friendly theme. Your task is to create a RESTful API, containerized with Docker, complemented by well-written tests and clear documentation.

### Key Requirements

- **Language**: Choose Golang, TypeScript, or Java.
- **API**: A single RESTful GET endpoint.
- **Docker**: Containerize the microservice.
- **Testing**: Implement at least one meaningful test.
- **Documentation**: Provide detailed instructions in `README.md`.

### The Challenge: AI & Sustainability API

Create a REST API with a single GET endpoint:

- **Endpoint**: `GET /universe-meaning/{param}`
  - **Response**: "This AI is eco-powered and sustainable. The meaning of the universe is {param}."

### Docker

- Provide a Dockerfile to containerize the service.
- Include instructions for building and running the container.

### Testing

- Write a test to verify the API's functionality.
- Include clear instructions to run the test in the documentation.

### Documentation

Your `README.md` should cover:

1. Setup instructions.
2. Design rationale.
3. Example usage of the API.

## Evaluation Criteria

- **Code Quality**: Clean, efficient, maintainable code.
- **Functionality**: The API performs as expected.
- **Testing**: The test should be relevant and well-structured.
- **Documentation**: Clear and concise, covering all necessary steps.

## Bonus: Store GET Parameter History

### Additional Task

Store a history of the parameters passed to your API in a database. You can use MongoDB, PostgreSQL, SQLite, or another database.

- **Database**: Store the history of `param` and any relevant metadata (e.g., timestamp).
- **Optional**: Add an endpoint to retrieve stored parameters.

### Documentation

Expand the `README.md` to include:

1. Database setup and integration.
2. (Optional) Documentation of the retrieval endpoint.

## Submission

- Host your code on a public platform (e.g., GitHub).
- Ensure the repository is accessible for review.
- Alternatively, zip and send your archive to the email provided during your interview.
