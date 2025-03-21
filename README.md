# PactFlow Python Coding Test

Welcome to this Python coding test. This test is designed to assess your ability to write clean, well-structured, and maintainable code. You will be tasked with adding some functionality to this codebase.

We will be looking for the following aspects:

1.  The readability and clarity of your code; including aspects such as:
    -   Naming conventions
    -   Code structure
    -   Comments
    -   Documentation
    -   Adherence to existing code
2.  The correctness of your code; including aspects such as:
    -   Handling of edge cases
    -   Error handling
    -   Testing
3.  The maintainability of your code; including aspects such as:
    -   Modularity
    -   Extensibility
    -   Reusability
4.  Your familiarity with standard development tools and practices; including aspects such as:
    -   Version control
    -   Creating and using virtual environments
    -   Documenting PRs and commits

Please fork this repository and submit your solution as a pull request. Your solution should pass the existing CI checks, and you should ensure that your code is tested. This project uses the [pytest](https://docs.pytest.org/en/stable/) testing framework.

## Development

This project uses [Hatch](https://hatch.pypa.io) for managing the development environment. The code is split across two packages:

-   `pypacter`: The core logic
-   `pypacter-api`: API wrapper

The structure of the project is as follows:

```text
pypacter/
├── pypacter-api/     <== API wrapper
│  ├── src/pypacter_api/
│  ├── tests/
│  ├── pyproject.toml
│  └── README.md
├── notebooks/       <== Jupyter notebooks (if any)
├── src/
│  └── pypacter/     <== Core logic
├── tests/
├── pyproject.toml
└── README.md
```

## Tasks

In the interview, you will be asked to complete one or two tasks, depending on the time available. You will have two engineers available to help you with any questions, and you are encouraged to ask for help for any clarification, questions, or guidance. The intent is to simulate the way we work at PactFlow, where we encourage collaboration and communication.

The specific details of the tasks will be provided to you during the interview, but may include any of the following:

-   Adding a new functionality to the core package
-   Adding a new endpoint to the API
-   Extending or enhancing an existing capability

You are encouraged to read the existing codebase and familiarize yourself with the structure. Please make sure that you are able to run the tests before the interview to maximize the time available for the tasks during the interview.
