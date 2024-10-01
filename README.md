NAME:NAVEENA

COMPANY:CODETECH IT SOLUTIONS

ID:CT08DS7280

DOMAIN:WEB DEVELOPMENT

DURATION:SEP-OCT 2024

OVERVIEW OF THE TASK :

TASK: CREATING A TO DO LIST WEB PAGE


![Screenshot 2024-10-01 223017](https://github.com/user-attachments/assets/0eb39d3f-5666-4af0-8375-12b43ec72155)

![Screenshot 2024-10-01 223052](https://github.com/user-attachments/assets/6c9d2544-d233-4b33-a1b8-3f1017fa6566)




#### **1. HTML Structure:**
- The `<head>` section contains the meta tags, title, and embedded CSS for styling.
- The `<body>` section contains the main interface for the To-Do List:
  - A title (`<h1>`) "To-Do List".
  - An input field (`<input>`) for users to enter new tasks.
  - A button (`<button>`) to add the task to the list.
  - An unordered list (`<ul>`) where tasks will be displayed dynamically as list items (`<li>`).

#### **2. CSS (Cascading Style Sheets):**
- **Styles the To-Do List App**:
  - Centers the to-do list in the middle of the screen using Flexbox.
  - Provides a clean, minimalistic design with a white background, rounded corners, and subtle shadows.
  - The task items are displayed in a simple list format with a button for removing tasks.
  - The completed tasks are styled with a line-through using the `.completed` class when a user clicks on a task.

#### **3. JavaScript:**
The embedded JavaScript handles the functionality of the app:
- **`addTask()` Function**: This is triggered when the user clicks the "Add" button.
  - The function retrieves the value from the input field and creates a new list item (`<li>`) for the task.
  - A "Remove" button is appended to each list item, allowing the user to delete the task when clicked.
  - Clicking on the task itself toggles its completion by adding/removing the `completed` class, which applies a line-through style.
  - After adding the task, the input field is cleared for a better user experience.

#### **Key Functionalities:**
1. **Add Task**:
   - The user enters a task in the input field.
   - The task is added to the list when the "Add" button is clicked or `addTask()` is called.

2. **Mark as Completed**:
   - Clicking on a task toggles the `completed` class, which applies a line-through, indicating that the task is finished.

3. **Remove Task**:
   - Each task comes with a "Remove" button that, when clicked, removes the task from the list entirely.

#### **User Experience (UX):**
- The application is clean and simple, ensuring an intuitive experience.
- Adding tasks, completing them, and removing them are all straightforward actions.
- Real-time feedback is provided when tasks are added or removed, and task completion is visually indicated.
