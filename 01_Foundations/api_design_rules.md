# API Design Rules

- All API calls go through a central ApiClient
- No direct HTTP calls inside UI
- Use models for request/response
- Handle errors at service layer
- Use DTO → Domain mapping
