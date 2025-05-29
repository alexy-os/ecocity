# Contributing to EcoCity

We welcome contributions to the EcoCity platform! This guide outlines the development process and standards.

## Development Setup

### Prerequisites
- Go 1.21+
- Node.js 18+
- Git

### Backend (Go)
```bash
cd backend
go mod download
go run main.go
```

### Frontend (React)
```bash
cd frontend
npm install
npm start
```

## Code Standards

### Go Backend
- Follow Go conventions and `gofmt` formatting
- Write tests for new functionality
- Use meaningful variable and function names
- Add comments for exported functions

### React Frontend
- Use TypeScript for type safety
- Follow React best practices and hooks patterns
- Implement responsive design
- Write unit tests with Jest/React Testing Library

## Pull Request Process

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Make your changes with clear commit messages
4. Run tests: `go test ./...` and `npm test`
5. Submit a pull request with description of changes

## Code Review

- All submissions require review
- Ensure code follows project standards
- Include tests for new features
- Update documentation as needed

## Issues

- Use GitHub issues for bug reports and feature requests
- Provide clear reproduction steps for bugs
- Include relevant system information 