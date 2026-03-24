## Iteration 2: Core Functionality 
The hardest interaction to implement was filtering the tasks by all, active, and completed. I had to understand how to store tasks in an array of objects and then use conditionals and filter() to decide which tasks should be shown on the page.  

In this project, I used JavaScript concepts such as variables, functions, arrays, objects, condtionals, event listeners, and DOM methods. I also used localStorage so the tasks would stay saved even after closing the page. 

One bug I found was that empty tasks could be added if the user clicked the button without typing anything. I fixed this by using trim() and showing an error message. Another bug was making sure that page updated correctly after deleting or completing a task, which I fixed by calling renderTasks() after each change. 