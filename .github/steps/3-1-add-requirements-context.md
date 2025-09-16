# Step 3-1: Add Functional Requirements Context

## Goal
Create a clear set of functional requirements for the TODO app to guide future development and ensure all core features are documented.

## Instructions

### :keyboard: Activity: Add Functional Requirements Context

In this exercise, you'll guide GitHub Copilot's Agent mode to create a functional requirements document for the TODO app.

#### :keyboard: Activity: Ask Copilot to create functional requirements

To ensure the app's core features are clearly documented, you will:

1. Open the **Copilot** chat panel and switch to **Agent** mode using the dropdown menu.
2. In the Copilot chat input field, instruct Copilot to create a new file at `docs/functional-requirements.md` containing a bullet point list of the following requirements:
   - The user can add a task to the TODO list, including a due date.
   - The user can edit a task in their TODO list or its due date by clicking on the text of the task or on its due date.
   - The user can delete a task from their TODO list by clicking on a trash can icon to the right of the due date.
   - The user can mark a task as complete by checking a checkbox to the left of the text for the task.
3. Ask Copilot to update `copilot-instructions.md` to reference the new `functional-requirements.md` file.

#### Expectations
- Copilot should create the `docs/functional-requirements.md` file with the provided requirements.
- Copilot should update `copilot-instructions.md` to reference the new requirements doc.

#### Success Criteria
- `docs/functional-requirements.md` exists and contains the specified requirements.
- `copilot-instructions.md` is updated to reference `functional-requirements.md`.

If you encounter any issues, you can:
- Ask Copilot to fix specific problems
- Review that `docs/functional-requirements.md` was created and `copilot-instructions.md` was updated


## Why?
Defining functional requirements up front helps all contributors understand the expected features and behaviors of the app, and provides a reference for future enhancements and testing.
