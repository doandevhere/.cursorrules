# TechStacks has been used in this project, and you are an expert developer in these
  - You read the `package.json` file to understand the tech stacks and which version is used in this project.

# Rules in thinking for models LLM
  - Always you think step by step, and don't skip any step.
  - Don't creative, let handle focus the correction of solution.
  - Always use `@Definitions` symbol to define the related information to the task.

# Rules working with the context
  - Split requirement to multiple small tasks(each task has 1000 tokens) and ordering them by priority.
  - You response list of tasks and their requirements with order in top of response.
  - You handle each task one by one, and don't handle multiple tasks at the same time.
  - You ask me review the task before continue handle next task.

# Rules to handle the task
  - You always read the task requirement and understand it before continue handle it.
  - You read to `package.json` file to understand the tech stacks and which version is used in this project.
  - You always review your changes(avoid issues can crash app, infinite loop, etc..) and follow bellow rules before continue handle the task.

# Rules working with code
  - Follow the SOLID principles.
  - Make the component as simple, small as possible, and don't use too many logic in component/file.
  - In parent folder, your create the sub-folder to handle the logic of components/pages. Like `parentFolder/{index.ts|tsx, utils/*, types/*, hooks/*, components/*, constants/*, etc,..}`.
  - Don't auto fix linting errors/warnings if don't required or related to the task.
  - Some task if you don't sure about solution, please ask me before continue handle it.
  - Don't lazy, always try to find the best solution for the task
  - Don't need to comment code, just write code and make it readable and easy to understand.
  - Always use `@Web` symbol to search the solution, to make sure the solution is correct with library version has been used in this project and best practice.

# Rules response to the question
  - Always answer in English, make sure it comfortable for intermediate English speaker.

# Rules commit message
  - Commit message should be in English.
  - [type of task] include chore, fix, feat, refactor, docs, style, test, ci, build, perf, revert, revert:
  - Commit message: [type of task]: [summary of the task]. Ex: feat: add new feature to the task.
  - Description format: `fileName: lineNumber: what change detail in lineNumber`. Ex: `src/pages/Home.tsx: 10: add props type to the component.`