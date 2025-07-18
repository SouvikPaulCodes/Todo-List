# Todo-List Web Application 📝

A modern, responsive Todo-List web application built with vanilla JavaScript, featuring project organization, task management, and local storage persistence.

## 🌟 Features

### Project Management
- **Create Projects**: Organize your todos into different projects
- **Project Descriptions**: Add detailed descriptions for each project
- **Project Navigation**: Quick sidebar navigation between projects
- **Delete Projects**: Remove projects with confirmation dialog

### Task Management
- **Add Todos**: Create tasks with names, due dates, priority levels, and notes
- **Priority Levels**: Set tasks as High, Medium, or Low priority
- **Due Date Tracking**: Visual indicators for overdue, due today, and upcoming tasks
- **Task Notes**: Add detailed notes to any task
- **Task Details**: View expanded task information in a modal
- **Delete Tasks**: Remove completed or unwanted tasks

### Smart Date Features
- **Date Comparison**: Uses the external `date-fns` library for accurate date calculations
- **Overdue Detection**: Automatically highlights overdue tasks in red
- **Due Today**: Special highlighting for tasks due today
- **Days Remaining**: Shows how many days until a task is due

### Data Persistence
- **Local Storage**: All data is saved using the Web Storage API
- **Automatic Saving**: Changes are automatically persisted
- **Session Recovery**: Your data persists between browser sessions

### User Interface
- **Responsive Design**: Works on desktop and mobile devices
- **Custom Fonts**: Beautiful typography with multiple custom font families
- **Color-Coded Priority**: Visual priority indicators
- **Hover Effects**: Interactive UI elements with smooth transitions
- **Modal Dialogs**: Clean popup interfaces for forms and confirmations

## 🚀 Live Demo

Experience the application live at: **https://souvikpaulcodes.github.io/Todo-List/**

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with custom fonts and responsive design
- **Vanilla JavaScript**: Core functionality and DOM manipulation
- **date-fns**: External library for date calculations and comparisons
- **Web Storage API**: Local data persistence
- **Webpack**: Module bundling and build process

## 📱 Responsive Design

The application is fully responsive and adapts to different screen sizes:
- **Desktop**: Optimal viewing with sidebar navigation
- **Tablet/Mobile**: Adjusted layout for smaller screens (breakpoint at 750px)

## 🎨 Custom Fonts

The application features several custom font families:
- **technologyregular**: Main headings
- **technologybold_italic**: Emphasized text
- **technologyitalic**: Italicized content
- **caladeabold**: Bold project elements
- **caladeabold_italic**: Bold italic styling
- **caladearegular**: Regular body text

## 🔧 Project Structure

```
Todo-List/
├── index.html          # Main application structure
├── main.js            # Bundled JavaScript (includes all functionality)
├── *.woff files       # Custom font files
├── README.md          # Project documentation
└── .gitignore         # Git ignore configuration
```

## 💾 Data Storage

All user data is stored locally in the browser using the Web Storage API. The data structure includes:
- Project information (name, description, ID)
- Todo items (name, due date, priority, notes, ID)
- Automatic serialization and deserialization

## 🖱️ User Interactions

### Creating Projects
1. Click "Add a new Project" in the sidebar
2. Enter project name and description
3. Click "Save" to create the project

### Adding Todos
1. Click the "+" button in any project
2. Fill in todo details (name, due date, priority, notes)
3. Click "Save" to add the todo

### Managing Tasks
- Click on any todo to view full details
- Use the "Remove Todo" button to delete tasks
- Visual indicators show priority and due date status

## 🌐 Browser Compatibility

The application works in all modern browsers that support:
- ES6+ JavaScript features
- CSS Grid and Flexbox
- Web Storage API
- Custom fonts (WOFF/WOFF2)

## 🔮 Future Enhancements

Potential features for future development:
- Task categories and tags
- Due time (not just date)
- Task sharing and collaboration
- Export/import functionality
- Dark/light theme toggle
- Task search and filtering
- Recurring tasks
- Task completion tracking

## 👨‍💻 Developer

Created by **SouvikPaulCodes**

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Hope you like it and can use it in your daily life accordingly!* ✨
