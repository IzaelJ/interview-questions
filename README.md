# Interview Questions

A collection of coding interview questions and solutions in C#/.NET 10.

## Prerequisites

- [mise](https://mise.jdx.dev/) (for .NET SDK management)
- Or .NET 10.0 SDK

## Setup

### Using mise (recommended)
```bash
# Clone the repository
git clone https://github.com/yourusername/interview-questions.git
cd interview-questions

# Install .NET SDK via mise
mise install

# Restore dependencies
dotnet restore
```

### Without mise

Install .NET 10.0 SDK from [dotnet.microsoft.com](https://dotnet.microsoft.com/), then:
```bash
dotnet restore
```

## Building
```bash
# Using mise
mise run build

# Or directly
dotnet build
```

## Running Tests
```bash
# Using mise
mise run test

# Or directly
dotnet test

# Watch mode
mise run watch
# Or: dotnet watch test --project InterviewQuestions.Tests
```

## Project Structure
```
interview-questions/
├── InterviewQuestions/          # Main library with solutions
└── InterviewQuestions.Tests/    # Unit tests
```
