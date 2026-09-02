# 📝 To-Do List App

A simple, beautiful, and functional to-do list application with local storage functionality. Your tasks are automatically saved and persist between browser sessions.

## Features

✨ **Core Features:**
- ✅ Add new tasks with ease
- ✔️ Mark tasks as complete/incomplete
- 🗑️ Delete individual tasks
- 🔍 Filter tasks (All, Active, Completed)
- 💾 Auto-save to browser local storage
- 📊 Task statistics (Total, Active, Completed)
- 🎨 Beautiful, responsive design
- 📱 Mobile-friendly interface

## How It Works

1. **Add Tasks**: Type in the input field and press Enter or click the Add button
2. **Complete Tasks**: Click the checkbox next to a task to mark it as done
3. **Delete Tasks**: Click the trash icon to remove a task
4. **Filter Tasks**: Use the filter buttons to show All, Active, or Completed tasks
5. **Clear Tasks**: Remove all completed tasks or clear everything at once
6. **Auto-Save**: All changes are automatically saved to browser local storage

## Local Storage

Your tasks are stored in the browser's local storage using the key `todoTasks`. The data persists until you:
- Manually clear browser data
- Click "Clear All" in the app
- Manually delete the local storage entry

### Data Structure

```json
[
  {
    "id": 1234567890,
    "text": "Task description",
    "completed": false,
    "createdAt": "9/2/2026, 12:00:00 PM"
  }
]
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/NeoNest-collab/todo-list-app.git
   ```

2. Open `index.html` in your web browser

3. Start adding tasks!

## Browser Compatibility

✅ Chrome/Edge (v4+)
✅ Firefox (v3.5+)
✅ Safari (v4+)
✅ Opera (v10.5+)
✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Project Structure

```
todo-list-app/
├── index.html      # HTML structure
├── styles.css      # Styling and animations
├── script.js       # Core application logic
└── README.md       # This file
```

## Keyboard Shortcuts

- **Enter** in input field: Add a new task
- Click **checkbox**: Toggle task completion
- Click **trash icon**: Delete a task
- Click **filter buttons**: Change task filter view

## Styling Details

- **Color Scheme**: Purple gradient background with clean white interface
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **Animations**: Smooth transitions and slide-in effects for better UX
- **Accessibility**: Good color contrast and semantic HTML

## Future Enhancements

- [ ] Task priority levels (High, Medium, Low)
- [ ] Due dates and reminders
- [ ] Task categories/tags
- [ ] Dark mode toggle
- [ ] Task editing capability
- [ ] Drag-and-drop to reorder
- [ ] Data export (JSON, CSV)
- [ ] Cloud sync functionality
- [ ] Multiple lists support
- [ ] Recurring tasks

## Tips for Best Experience

💡 **Enable Notifications**: Allow browser notifications for task reminders
💡 **Regular Backups**: Export your tasks periodically
💡 **Keep List Clean**: Archive completed tasks occasionally
💡 **Use Categories**: Use naming conventions like "Work: Task" or "Personal: Task"

## Troubleshooting

**Q: My tasks disappeared!**
A: Check if you cleared your browser's local storage/cache. Consider backing up important data.

**Q: Why don't I see animations?**
A: Make sure CSS is loaded correctly and your browser supports CSS animations (all modern browsers do).

**Q: Can I sync across devices?**
A: Currently, data is stored locally per browser. Consider the future cloud sync feature!

## License

MIT License - Feel free to use and modify for your projects!

## Credits

Built with ❤️ using HTML, CSS, and JavaScript.

No dependencies required! Pure vanilla JavaScript with browser APIs.

---

**Made with ❤️ for productivity** 📝✨