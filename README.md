# CI ISA Review

Welcome to the coding challenge. Here is the place that you will know how good you are at tech.
We're all here to help you. Don't be nervous :)

---

# What is this?

This is a white board coding challenge so that we can see how you use your skills to solve 
a specific problem. You'll know how good you have trained with React, and perhaps know how an tech interview
would look like (we hope so).

### You can:

- search for supporting in google about some library documentations.
- ask for hints if you get stuck at some points.

### You should:

- speak out loud your thinking. We care about how you solve the problem.
- suggest your ideas to improve the apps.
- aware of time pressure. Cause we have a limited amount of time.

### You don't need to:

- write perfect code. You can make some mistakes and it's totally okay.
- complete the app. But please try your best to push your limit.

### You have to:

- share your screen. We need to control your progress.

That's all. Good luck!

---

# Tasks:

Before start working, please take 3 minutes to look into the source code and the UI...

### 1. Complete the creating task & marking as done behavior:
When user create a task with form submission, The list should be updated with new created entry.
When user click the checkbox, item's status should be updated to "done" / "not finished"
And the total number of undone tasks on top should be updated.

### 2. Show the not finished tasks only
Create a checkbox on top, saying "Not finished only". When it's checked, we show only the going task only.
When it's unchecked, we show both done and not finsished tasks.
Find a way to use URL to fast access the going tasks. For example: `<app-domain.com>?withDone=1` for getting all
task (done tasks included) 

### 3. Store all the tasks permantly and load them in the first place.
All the task should be storaged inside the LocalStorage. When user first come to the app, we load everything
from storage to the app.

### 4. Attach a due date to a task
A task could have a due date for reminding later. Storage this information and show how many day left until 
the due date on each item.

### 5. Languague switching
Change the UI languege with the language switcher

### 6. Reorder the list
Users might want to organize their task list. Give them ability to reorder the list whatever they want.
