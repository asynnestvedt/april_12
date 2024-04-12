# Basic Coding Exercise: Eco-Powered AI Microservice

## Introduction

Dive into a challenge that blends your technical expertise with a flair for sustainability and innovation. We're seeking an elegantly designed microservice, built in **Golang**, **TypeScript**, or **Java**, which embodies the spirit of technology and advanced RESTful design, complemented by Docker containerization, strategic testing, and articulate documentation.

### Your Mission

Develop a microservice that represents the next step in AI-driven, eco-friendly technology. The service should offer a simple yet impactful REST API endpoint that delivers a message combining eco-awareness and a playful nod to the profound mysteries of the universe.

### Technical Requirements

- **Programming Language**: Choose from Golang, TypeScript, or Java.
- **API Design**: A single, meaningful RESTful GET endpoint.
- **Containerization**: Use Docker for deployment.
- **Testing**: Develop at least one relevant test.
- **Documentation**: Provide clear and detailed documentation.

## Challenge Details

### Eco-Powered AI API Endpoint

Create a RESTful GET endpoint that delivers an insightful message about sustainability and the universe:
- `GET /universe-meaning/{param}`: Returns a message: "This AI is super green eco-powered and sustainable. The meaning of the universe is {param}."

### Docker Containerization

- Package your microservice in a Docker container.
- Include a Dockerfile and detailed instructions for building and running the container.

### Testing

- Write a test for your API endpoint.
- Describe how to run the test in your documentation.

### Documentation: Your Masterpiece

- Your `README.md` should illuminate your development journey, including:
  - Instructions for setup and operation.
  - An overview of your design choices.
  - API endpoint documentation with example usage.

## Evaluation Criteria

- **Code Quality**: Display your skill in crafting clean, efficient code.
- **Functionality**: Your service should perform as expected, with a focus on the unique endpoint.
- **Testing Depth**: Demonstrate the effectiveness of your test.
- **Documentation Excellence**: Your documentation should be comprehensive and engaging.

## Submission

- Share your work on any public code hosting platform.
- Ensure the repository is accessible for evaluation.


## Bonus Points: GET Parameters History Storage

### Enhance Your Creation

To elevate your solution and showcase your adeptness in handling data persistence, we introduce an additional challenge: store the history of GET parameters in a database of your choice.

### Database Options

Feel free to choose from a variety of databases, such as:
- MongoDB
- PostgreSQL
- SQLite
- Or any other database you prefer

### Implementation Requirements

- **Database Integration**: Seamlessly integrate a database to store the history of GET parameters received by your API endpoint.
- **Data Structure**: Design a schema or data model that efficiently captures the GET parameters and any relevant metadata (like timestamp, user ID, etc.).
- **Retrieval Endpoint (Optional)**: Consider adding another endpoint to retrieve the history of stored parameters.
- **Resilience and Efficiency**: Ensure your implementation is robust and performs efficiently under varying loads.

### Extended Documentation

- Expand your `README.md` to include:
  - Instructions on setting up the database and integrating it with your microservice.
  - (If implemented) Documentation of the retrieval endpoint.

### Evaluation of Bonus Points

- **Database Integration Skills**: Demonstrate your ability to integrate and utilize a database effectively.
- **Schema Design**: Show how your data model is optimized for the task.
- **Code Elegance and Efficiency**: Maintain code quality and efficiency with the added complexity.
- **Enhanced Documentation**: Your documentation should now reflect the additional features and provide clear guidance on them.

Embrace this bonus challenge to push the boundaries of your microservice's capabilities and demonstrate a comprehensive understanding of data persistence and management. We're excited to see how you incorporate these features into your solution!
