# API mocking platform

At Crest Data, I designed and built a mock server that creates endpoints from OpenAPI 3.0 and Postman specifications. Frontend and QA teams use it when they need to work with an API before the backend is ready.

The platform supports:

- State shared across multiple APIs.
- Weighted and randomized responses.
- Conditional responses and rate limiting.
- Error scenarios such as malformed JSON and oversized payloads.
- MCP integration to help generate endpoints and example responses from user requests.

It was adopted across the organization's QA teams and is also used by customers. It reduced the work involved in creating and maintaining test fixtures.

**Stack:** Java, Spring Boot, Redis, Docker, MCP.

[Back to profile](../README.md)
