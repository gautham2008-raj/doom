# To-Do List Application

A beautiful, fully functional to-do list application with local storage functionality.

## Features

- ✅ Add, complete, and delete tasks
- 💾 Automatic local storage - tasks persist across browser sessions
- 🎨 Beautiful gradient UI with smooth animations
- 📱 Fully responsive design (mobile, tablet, desktop)
- 🔍 Filter tasks (All, Active, Completed)
- 📊 Real-time task statistics
- 🔒 XSS protection

## How to Use

1. **Add a Task**: Type your task in the input field and click "Add Task" or press Enter
2. **Complete a Task**: Check the checkbox next to a task to mark it as completed
3. **Delete a Task**: Click the "Delete" button next to any task
4. **Filter Tasks**: Use the filter buttons to view All, Active, or Completed tasks
5. **Clear Completed**: Click "Clear Completed" to remove all finished tasks at once

## Technology Stack

- HTML5
- CSS3 (with gradients, animations, and flexbox)
- Vanilla JavaScript (ES6+)
- Browser Local Storage API

## Deployment

This app is deployed on Vercel and GitHub Pages.

### Live URLs:
- **Vercel**: [Your Vercel deployment URL]
- **GitHub Pages**: https://gautham2008-raj.github.io/drdoom/

## Local Storage

All your tasks are automatically saved to your browser's local storage under the key `todoList`. This means:
- Your tasks won't be lost if you close the browser
- Each browser/device stores its own tasks
- No data is sent to any server

## Files

- `index.html` - Main HTML structure
- `styles.css` - Styling and animations
- `script.js` - JavaScript functionality
- `vercel.json` - Vercel deployment configuration

## Created by

@gautham2008-raj
