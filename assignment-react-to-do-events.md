#### Questions

> Before You Begin: Create a new Git feature branch for this assignment. See Git Checkpoint Workflow: Before Each Assignment for details.

1. Read React's documentation on Forms.
2. Our to-do app is missing one key feature: The ability to delete to-do items. Add this feature to your app. Make sure to:
  1. Add a delete button to the ToDo component.
  2. Define a deleteTodo method on the App component. This method should call this.setState() and pass it a new array that doesn't have the to-do item being deleted. Consider using the .filter() array method to accomplish this without mutating state – do not use .splice(), which is a mutable method, unless making a copy of the array first.
  3. Pass the deleteTodo method to the ToDo component as a prop.
  4. Add an onClick event listener to the delete button, and have it call deleteTodo, passing it the index of the to-do.
  5. When You're Done: Commit your assignment work in Git. See Git Checkpoint Workflow: After Each Assignment for details.
