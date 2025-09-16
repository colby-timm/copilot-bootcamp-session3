# Step 2-4: Add Coding Guidelines

## Goal
Document clear coding guidelines for the TODO app to ensure code consistency, quality, and maintainability across the project.

## Instructions

### :keyboard: Activity: Add Coding Guidelines

In this exercise, you'll guide GitHub Copilot's Agent mode to create a coding guidelines document for the TODO app.

#### :keyboard: Activity: Ask Copilot to create coding guidelines

To ensure the project's coding approach is well documented, you will:

1. Open the **Copilot** chat panel and switch to **Agent** mode using the dropdown menu.
2. Instruct Copilot to create a new file at `docs/coding-guidelines.md` with a narrative summary of the project's coding style and quality principles.  
   The summary should cover:
   - General formatting rules (such as indentation, semicolons, line length, string quotes, trailing commas, and spacing).
   - JavaScript/TypeScript conventions (such as using `const` and `let`, and avoiding `var`).
   - Import organization (such as grouping and ordering imports logically).
   - A suggestion to use a linter to enforce these guidelines.
   - Key code quality principles, such as writing readable and maintainable code, using clear names, following DRY principles, breaking complex logic into smaller functions, documenting public APIs, and following security and accessibility best practices.
   You can use your own words when instructing Copilot, as long as the intent is clear.
3. Ask Copilot to update `copilot-instructions.md` to reference the new `coding-guidelines.md` file.

#### Expectations
- Copilot should create the `docs/coding-guidelines.md` file with a narrative summary of the project's coding style, conventions, import organization, code quality principles, and a suggestion to use a linter.
- Copilot should update `copilot-instructions.md` to reference the new coding guidelines doc.

#### Success Criteria
- `docs/coding-guidelines.md` exists and contains a narrative summary of the project's general formatting, conventions, import organization, code quality principles, and a suggestion to use a linter.
- `copilot-instructions.md` is updated to reference `coding-guidelines.md`.

If you encounter any issues, you can:
- Ask Copilot to fix specific problems
- Review that `docs/coding-guidelines.md` was created and `copilot-instructions.md` was updated

## Why?
Clear coding guidelines and code quality principles help all contributors write consistent, maintainable, and high-quality code, making collaboration easier and the project more robust.
