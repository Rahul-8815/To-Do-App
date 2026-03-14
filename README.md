# To-Do App

A simple and interactive To-Do List application built with vanilla JavaScript, HTML, and CSS.

## Features

- **Add Tasks**: Enter tasks through an input field and add them to your list
- **Delete Tasks**: Remove completed or unwanted tasks with a delete button
- **Dynamic UI**: Tasks are dynamically created and removed from the DOM
- **Event Delegation**: Efficient event handling using event delegation pattern

## Technologies Used

- **HTML5**: Structure and markup
- **CSS3**: Styling (style.css)
- **JavaScript (ES6)**: Core functionality and DOM manipulation

## Project Structure

```
To-Do-App/
├── index.html    # Main HTML structure
├── app.js        # JavaScript logic for task management
├── main.js       # Additional JavaScript file
├── style.css     # Styling for the application
└── README.md     # Project documentation
```

## How It Works

1. **Adding Tasks**: 
   - User enters a task in the input field
   - Clicks the "Add Task" button
   - Task is appended to the list with a delete button

2. **Deleting Tasks**:
   - Each task has a delete button
   - Clicking delete removes the task from the list
   - Uses event delegation on the parent `<ul>` element

## Installation & Usage

1. Clone or download the repository
2. Open `index.html` in any modern web browser
3. Start adding and managing your tasks!

## Code Highlights

- **DOM Manipulation**: Uses `createElement()`, `appendChild()`, and `remove()` methods
- **Event Listeners**: Implements click events for adding and deleting tasks
- **Event Delegation**: Efficiently handles delete operations on dynamically created elements
- **Input Clearing**: Automatically clears input field after adding a task

## Browser Compatibility

Works on all modern browsers that support ES6 JavaScript.

## Future Enhancements

- Local storage persistence
- Task editing functionality
- Task completion toggle
- Styling improvements
- Task categories/priorities

## License

Open source - feel free to use and modify as needed.
