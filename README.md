# IT 126 – Module 3, Lesson 2
## Analysis

### 1. What happened to the task titles when you added them to the list?
The task titles were added to the list and displayed on the screen.

### 2. Why could the application display the tasks while it was running?
The task titles remained in the list while the application was running so it could be shown on the screen.

### 3. What happened after the application process ended and the application was relaunched?
The task was gone because it was not saved. When the app started again the list was empty.

### 4. Would keeping the list inside a StatefulWidget automatically make the tasks persistent? Explain your answer.
No. A StatefulWidget can update state list while the app is running, but it cannot save the task permanently by itself.

### 5. What would the application need to do to preserve the tasks between sessions?
The application need to save task in a file, or database and load them again when the apps starts.

### 6. If the application eventually stored hundreds or thousands of tasks, what problems might arise from managing all the data manually in memory?
It could be harder to find, edit, and delete tasks. The app could also become harder to manage an the tasks would disappear when the app closes. A database can help organize and manage the tasks.

### 7. How could separating the operations that save and retrieve tasks from the UI make the application easier to maintain?
The UI handles displaying the tasks, while a separate repository handles saving and loading them. This makes the code easier to understsand and update.

