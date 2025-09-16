# Step 2-3: Add Testing Guidelines

## Goal
Document clear testing guidelines for the TODO app to ensure code quality and reliability across the project.

## Instructions

### :keyboard: Activity: Add Testing Guidelines

In this exercise, you'll guide GitHub Copilot's Agent mode to create a testing guidelines document for the TODO app.

#### :keyboard: Activity: Ask Copilot to create testing guidelines

To ensure the project's testing approach is well documented, you will:

1. Open the **Copilot** chat panel and switch to **Agent** mode using the dropdown menu.
2. Instruct Copilot to create a new file at `docs/testing-guidelines.md` with the following summary and requirements:

   The project follows these testing principles:
   - Tests should give confidence that the code works as expected.
   - Tests should act as documentation for code behavior.
   - Tests should catch regressions early.
   - Tests should be maintainable and not brittle.
   - All new features should include appropriate tests.

   The project uses several types of tests:
   - **Unit tests** focus on individual functions, components, or modules in isolation. Each test should cover one thing, mock external dependencies, and be fast and lightweight. Unit tests are required for both back-end and front-end code.
   - **Integration tests** should be written using mock data to verify that different parts of the system work together as expected.
   - **End-to-end functional testing** is expected to ensure the application works correctly from the user's perspective.
3. Ask Copilot to update `copilot-instructions.md` to reference the new `testing-guidelines.md` file.

#### Expectations
- Copilot should create the `docs/testing-guidelines.md` file with a narrative summary of the project's testing practices and requirements.
- Copilot should update `copilot-instructions.md` to reference the new testing guidelines doc.

#### Success Criteria
- `docs/testing-guidelines.md` exists and contains a summary of `testing-practices.md` plus the requirements for unit, integration, and end-to-end testing.
- `copilot-instructions.md` is updated to reference `testing-guidelines.md`.

If you encounter any issues, you can:
- Ask Copilot to fix specific problems
- Review that `docs/testing-guidelines.md` was created and `copilot-instructions.md` was updated

## Why?
Clear testing guidelines help all contributors maintain high code quality, catch bugs early, and ensure the application works as intended.
