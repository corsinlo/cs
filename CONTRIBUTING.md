# Contributing Guidelines

## Development Setup

### Option 1: Dev Container (Recommended)
1. Install Docker and VS Code with Dev Containers extension
2. Open project in VS Code
3. Click "Reopen in Container" when prompted
4. Everything will be configured automatically

### Option 2: Local Development
1. Install Java 21, Node.js 20, and Docker
2. Clone the repository
3. Run `./run.sh` to start the application

## Code Standards

### Backend (Java/Spring Boot)
- Follow Java naming conventions
- Use 4 spaces for indentation
- Add JavaDoc for public methods
- Write unit tests for new services

### Frontend (React/TypeScript)
- Use TypeScript for type safety
- Follow React functional component patterns
- Use 2 spaces for indentation
- Add prop types and interfaces

### Database
- Use descriptive column names
- Add proper foreign key constraints
- Index frequently queried columns

## Testing
- Run backend tests: `cd backend && mvn test`
- Run frontend tests: `cd frontend && npm test`
- All tests should pass before submitting

## Pull Request Process
1. Create feature branch from main
2. Make your changes
3. Add/update tests
4. Ensure all tests pass
5. Submit pull request with clear description

## Code Review Guidelines
- Focus on logic correctness
- Check for security issues
- Verify test coverage
- Review documentation updates