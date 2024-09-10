# todo-list-app
This is a simple Todo List App built using JavaScript and DOM manipulation.

Functionality:- The app allows users to:

Add new todo items by submitting a form with a text input
Mark todo items as done by clicking the "Done" button
Remove todo items by clicking the "Remove" button

Code Overview:- The code consists of two main event listeners:

Form Submission: When the form is submitted, the app prevents the default form submission behavior and creates a new todo item with the input text. The new todo item is then appended to the todo list.

Todo List Click: When the todo list is clicked, the app checks if the user clicked on the "Remove" or "Done" button. If the "Remove" button is clicked, the corresponding todo item is removed from the list. If the "Done" button is clicked, the text of the corresponding todo item is struck through to indicate that it's done.


Code Structure:-The code is organized into two main sections:

Form Event Listener: The first section sets up an event listener for the form submission event. It gets the input text, creates a new todo item, and appends it to the todo list.


Todo List Event Listener: The second section sets up an event listener for the todo list click event. It checks the target of the click event and performs the corresponding action (remove or mark as done).


Variables and Selectors:- The code uses the following variables and selectors:

todoForm: The form element with the class form-todo


todoInput: The input element with the type text inside the form


todoList: The element with the class todo-list that contains the todo items


newTodoText: The text input by the user



newLi: The new todo item element created dynamically



newLiInnerHtml: The HTML content of the new todo item element


e: The event object passed to the event listeners
