# To-Do App

A modern, feature-rich to-do application built with vanilla HTML, CSS, and JavaScript. Manage your daily tasks efficiently with an intuitive and responsive interface.

## Features

✨ **Add Tasks** - Quickly add new tasks to your to-do list
✅ **Mark Complete** - Check off completed tasks with a single click
🗑️ **Delete Tasks** - Remove tasks you no longer need
🔍 **Filter Options** - View all tasks, active tasks, or completed tasks
💾 **Persistent Storage** - Tasks are saved locally using browser localStorage
📊 **Task Statistics** - Real-time count of total, active, and completed tasks
📱 **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
🎨 **Modern UI** - Beautiful gradient design with smooth animations

## How to Use

1. **Open the App**: Simply open `index.html` in your web browser
2. **Add a Task**: Type your task in the input field and press Enter or click the "Add" button
3. **Mark Complete**: Click the checkbox next to a task to mark it as complete
4. **Delete Task**: Click the "Delete" button to remove a task
5. **Filter Tasks**: Use the filter buttons to view different task states:
   - **All**: Show all tasks
   - **Active**: Show only incomplete tasks
   - **Completed**: Show only completed tasks

## Technical Details

### Technologies Used
- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with gradients and animations
- **Vanilla JavaScript** - Pure JS without any frameworks or libraries

### Browser Storage
The app uses `localStorage` API to persist tasks between browser sessions. Tasks are automatically saved whenever you:
- Add a new task
- Mark a task as complete/incomplete
- Delete a task

### Code Structure
- **Single HTML file** - Everything (HTML, CSS, JavaScript) is contained in `index.html`
- **No dependencies** - Built with vanilla JavaScript, no external libraries required
- **XSS Protection** - HTML special characters are escaped to prevent XSS attacks

## Features Breakdown

### Task Management
- Add tasks with keyboard (Enter key) or button click
- Toggle task completion status
- Delete tasks instantly
- Empty state message when no tasks are available

### Filtering System
- Dynamic filtering without page reload
- Active filter button highlighting
- Instant UI update on filter change

### Statistics
- Real-time count of total tasks
- Live count of active (incomplete) tasks
- Live count of completed tasks

## Responsive Design

The app is fully responsive and adapts to different screen sizes:
- **Desktop**: Full-featured interface with all elements visible
- **Tablet**: Optimized layout for medium screens
- **Mobile**: Stacked layout with touch-friendly buttons

## Future Enhancements

Potential features for future versions:
- Task due dates
- Task priority levels
- Task categories/tags
- Dark mode
- Task editing capability
- Drag and drop reordering
- Export/import tasks

## Browser Compatibility

Works on all modern browsers:
- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Free to use and modify for personal or commercial projects.

## Author

Created by Satyaprasad Naik

---

**Enjoy organizing your tasks!**
