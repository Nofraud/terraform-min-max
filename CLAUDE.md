# Development Guidelines

## Testing Philosophy

This project follows **Test-Driven Development (TDD)** principles:

1. Write tests first before implementing features
2. Run tests frequently during development
3. Ensure all tests pass before completing any task

## Required Workflow

After making ANY code change, you MUST run `npm test` to validate that no tests were broken, unless you are intentionally creating failing tests as part of TDD.

**Exception**: When following TDD, you may create failing tests first, but you must implement the functionality to make them pass before completing the task.
