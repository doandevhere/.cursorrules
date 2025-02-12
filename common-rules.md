

# YOU ALWAYS FOLLOW STEPS BELOW WHEN GET ANY REQUEST FROM USER

1. Get project information stage
  - First time you join the project, let's read overview of the project and create new `PROJECT_INFO.md` file
  - If the `PROJECT_INFO.md` file exists, you should read `PROJECT_INFO.md` and try to read codebase to understand the project(remember update the file if you have new information). It's helpful for you to understand the project and the codebase.
  - If the `PLAN_TASK.md` file exists, you should read the `PLAN_TASK.md` file to understand the task plan and stage of task.
  - If the `LESSON_LEARNED.md` file exists, you should read the `LESSON_LEARNED.md` file to understand the lesson learned.

2. Analysis request stage
  - You should analyze the request and understand the task.
  - If requirement not clear, you should ask user to clarify the requirement until 90-95% sure about the task.
  - Collect keywords and related files to understand the task.
  - Loop until 90-95% sure about the task.

3. Make plan to implement task stage
  - From the keywords and related files, you should make a plan to implement the task step by step(small as possible).
  - Detect and sort priority tasks
  - Write the plan detail before implement task.
  - Write the plan in `PLAN_TASK.md` file.
  - Format the plan file: `Plan complete task [user_task] - [project]
    - [1]: [content task number 1]
      - Related files: [file 1, file 2, ...]
      - Current status: [Planning/Implementing/Reviewed]
      - Dependencies: [List any blockers]
    - [2]: [content task number 2]
    - Related files: [file 1, file 2, ...]
    - Current status: [Planning/Implementing/Reviewed]
    - Dependencies: [List any blockers]
    - ...
  - Give user the plan detail.`

4. Implement task stage
  - Before implement task specific, you should update status of task in `PLAN_TASK.md` file.
  - Implement task step by step(top to bottom in `PLAN_TASK.md` file).
  - Follow the SOLID, DRY principle.
  - DO NOT handle parallel tasks. Make sure the task before is completed and has been reviewed.
  - Write the code detail before implement task.

5. Review task stage
  - Review the code use strict standard. Make sure the code is clean and easy to understand. No crash/error ability. Loop review until 90-95% sure.
  - Collect lesson learned in `LESSON_LEARNED.md` file. JUST NOTE IF TASK IS COMPLEX OR YOU TRY MANY TIMES AND STILL NOT SUCCESS UNTIL USER CONFIRMED.

6. Update `PLAN_TASK.md` file after implement task for other context can continue handle task

7. Loop [4, 5, 6, 7] step by step until task of user is completed and you have 90-95% sure about the task.

