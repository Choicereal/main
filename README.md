# Team Collaboration Guidelines

This document outlines the collaboration rules and best practices for backend and frontend teams working together on this project.

## General Guidelines

- Use English for all code, comments, and documentation
- Follow Git Flow branching strategy
- Create descriptive commit messages with prefixes (feat, fix, docs, style, refactor, test, chore)
- Review pull requests within 24 hours
- Maintain up-to-date documentation

## Backend Team Guidelines

### Code Structure
- Follow Django and DRF best practices
- Organize code into modular, reusable components
- Implement comprehensive unit tests (aim for >80% coverage)
- Document all API endpoints using OpenAPI/Swagger

### API Development
- Design RESTful APIs with consistent naming conventions
- Use versioning for all APIs (e.g., /api/v1/)
- Implement proper error handling and status codes
- Provide detailed API documentation with request/response examples
- Notify frontend team of any API changes before implementation

### Database
- Use migrations for all database changes
- Optimize queries for performance
- Document database schema changes
- Use PostgreSQL features appropriately

## Frontend Team Guidelines

### Code Structure
- Follow React best practices and patterns
- Use TypeScript for type safety
- Implement component-based architecture
- Write unit and integration tests for components

### UI/UX Development
- Use a design system for consistent UI
- Implement responsive designs for all screen sizes
- Follow accessibility standards (WCAG 2.1)
- Optimize performance (lazy loading, code splitting)

### API Integration
- Use a centralized API client for all requests
- Implement proper error handling and loading states
- Cache API responses when appropriate
- Use mock data for development when APIs are not ready

## Communication Protocols

### Daily Standups
- Share progress, blockers, and plans
- Identify cross-team dependencies

### Sprint Planning
- Define clear acceptance criteria for all tasks
- Estimate tasks collaboratively
- Identify technical dependencies between teams

### Integration Testing
- Conduct regular integration testing sessions
- Document and track integration issues
- Collaborate on fixing integration problems

## CI/CD Pipeline

- All code must pass automated tests before merging
- Frontend and backend deployments should be coordinated
- Use feature flags for gradual rollouts
- Monitor production deployments for issues

## Conflict Resolution

- Address technical disagreements with data and research
- Escalate unresolved issues to tech leads or project manager
- Document architectural decisions and their rationales
