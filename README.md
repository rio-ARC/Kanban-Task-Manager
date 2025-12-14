# Kanban Task Board

A simple, responsive Kanban task management application with an integrated calendar view, built with HTML, CSS (Tailwind), and JavaScript.

## Live Demo

[View the live application](https://kanbantaskmanager-sooty.vercel.app/)

## Features

- **Task Management**: Create, edit, and delete tasks across three columns: To Do, In Progress, and Done.
- **Drag & Drop**: Easily move tasks between columns using drag-and-drop functionality.
- **Calendar Integration**: View tasks with deadlines on a monthly calendar with highlights for today and deadline days.
- **Dark/Light Mode**: Toggle between light and dark themes with automatic system preference detection.
- **Notifications**: Get notified about upcoming deadlines (tasks due tomorrow).
- **Completion Celebrations**: Enjoy confetti and modal celebrations when tasks are completed.
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices.
- **Local Storage**: Tasks and theme preferences are saved locally in your browser.

## How to Use

1. **Open the Application**: Open `index.html` in your web browser.
2. **Add Tasks**: Use the "Add a New Task" form to create tasks with optional deadlines.
3. **Manage Tasks**: Drag tasks between columns or delete them using the × button.
4. **View Calendar**: Navigate through months to see task deadlines highlighted.
5. **Toggle Theme**: Click the theme toggle button (moon/sun icon) in the top-right or press 'T' to switch modes.
6. **Keyboard Shortcuts**:
   - Press 'T' to toggle between light and dark modes (when not typing in inputs).

## Technologies Used

- **HTML5**: Structure and content
- **CSS3**: Styling with Tailwind CSS framework
- **JavaScript (ES6+)**: Functionality and interactivity
- **Tailwind CSS**: Utility-first CSS framework for responsive design
- **Canvas Confetti**: For celebration effects
- **Local Storage API**: For data persistence

## Browser Support

Works in all modern browsers that support ES6+ features, drag-and-drop, and local storage.

## File Structure

```
/
├── index.html          # Main application file
└── README.md           # This file
```

## Customization

The application uses Tailwind CSS classes for styling. You can customize colors, fonts, and layout by modifying the inline styles and classes in `index.html`.

## Contributing

Feel free to fork this project and submit pull requests with improvements or bug fixes.

## License


This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
