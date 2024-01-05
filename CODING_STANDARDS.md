# Coding Standards for C# MAUI Project

This document outlines the coding standards and best practices for RoutineRanger C# MAUI project, adhering to Microsoft's recommended guidelines.

## General Principles

- **Readability and Maintainability**: Code should be easy to read and maintain.
- **Consistency**: Adhere to the established coding conventions and patterns in the project.
- **Best Practices**: Follow best practices as recommended by Microsoft and the broader C# community.

## C# Coding Conventions

- **Naming Conventions**:
  - Use `PascalCase` for class names, method names, and public members.
  - Use `camelCase` for local variables and method arguments.
- **Brace Style**:
  - Use the [Allman style](https://en.wikipedia.org/wiki/Indentation_style#Allman_style) braces, where braces start on a new line.
- **Use Implicitly Typed Local Variables**: Use `var` when the type of the variable is obvious from the right side of the assignment.
- **Error Handling**:
  - Prefer exceptions over returning error codes.
  - Use `try-catch` blocks judiciously.

## .NET MAUI Specific Standards

- **MVVM Pattern**:
  - Follow the Model-View-ViewModel (MVVM) pattern to promote separation of concerns.
- **Asynchronous Programming**:
  - Use `async` and `await` for asynchronous programming to keep the UI responsive.
- **Resource Management**:
  - Use resource dictionaries for styles and commonly used values to ensure consistency across the app.

## Code Formatting

- **Use Spaces Over Tabs**: Configure the editor to insert spaces rather than tabs.
- **Line Length**: Prefer lines to be no longer than 120 characters.

## Commenting and Documentation

- **XML Documentation Comments**: Use `///` for method documentation that can be read by IntelliSense.
- **In-line Comments**: Use them sparingly and only when necessary to explain complex logic or decisions.

## Version Control

- **Commits**: Write clear, concise, and descriptive commit messages.
- **Branches**: Use feature branches and merge requests for new features or bug fixes.

## Testing

- **Unit Testing**: Write unit tests for core logic and new features.
- **UI Testing**: Employ UI tests for critical user flows and interactions.

## Continuous Integration and Deployment

- **Build and Test Automation**: Use CI/CD pipelines to automate building, testing, and deployment.

## References

- [C# Coding Conventions (Microsoft Docs)](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions)
- [.NET MAUI Fundamentals (Microsoft Docs)](https://docs.microsoft.com/en-us/dotnet/maui/fundamentals/)

Please adhere to these standards for contributing to RoutineRanger to maintain code quality and consistency.
