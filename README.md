# TaskFlow - Advanced Task Management Application

A modern, responsive task management web application built with vanilla JavaScript, HTML5, and CSS3. Features a sleek UI with animations, dark mode support, and advanced task organization capabilities.

## 🚀 Features

### Core Functionality
- ✅ **Add Tasks** - Create tasks with title, description, priority, category, and due dates
- ✅ **Edit Tasks** - Click on task titles to edit them inline
- ✅ **Complete Tasks** - Mark tasks as complete/incomplete with checkboxes
- ✅ **Delete Tasks** - Remove tasks with confirmation dialog
- ✅ **Persistent Storage** - Tasks saved to localStorage automatically

### Advanced Features
- 🎯 **Priority Levels** - High, Medium, Low priority with color coding
- 📂 **Categories** - Organize tasks by Personal, Work, Shopping, Health
- 📅 **Due Dates** - Set and track task deadlines with overdue indicators
- 🌙 **Dark Mode** - Toggle between light and dark themes
- 📊 **Statistics Dashboard** - Real-time task statistics (Total, Active, Completed)
- 🔍 **Smart Filtering** - Filter tasks by status (All, Active, Completed)
- 📱 **Responsive Design** - Works perfectly on desktop, tablet, and mobile

### User Experience
- 🎨 **Smooth Animations** - CSS animations for all interactions
- 🔔 **Toast Notifications** - User feedback for all actions
- ♿ **Accessibility** - ARIA labels, semantic HTML, keyboard navigation
- 🔒 **Security** - XSS protection with HTML escaping
- ⚡ **Performance** - Optimized rendering and localStorage operations

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, Vanilla JavaScript (ES6+)
- **Storage**: Browser localStorage API
- **Styling**: Modern CSS with Flexbox/Grid, CSS Animations
- **Accessibility**: ARIA attributes, semantic HTML
- **Responsive**: Mobile-first design with media queries

## 📁 Project Structure

```
TaskFlow/
├── index.html          # Main application file
├── README.md          # Project documentation
└── assets/            # (Future) Static assets
```

## 🎯 Development Highlights

### Code Quality
- Clean, modular JavaScript with proper error handling
- Semantic HTML5 structure
- CSS custom properties and modern selectors
- Cross-browser compatibility

### Best Practices
- Separation of concerns (HTML/CSS/JS)
- Event delegation and modern DOM manipulation
- Input validation and sanitization
- Progressive enhancement

### Performance Optimizations
- Efficient DOM updates with minimal reflows
- Debounced localStorage operations
- Optimized CSS animations
- Lazy loading considerations

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/taskflow.git
   cd taskflow
   ```

2. **Open in browser**
   - Open `index.html` in any modern web browser
   - No build process or dependencies required!

3. **Start using**
   - Add your first task
   - Try the dark mode toggle
   - Test on different screen sizes

## 📱 Browser Support

- Chrome 70+
- Firefox 65+
- Safari 12+
- Edge 79+

## 🔧 Customization

### Adding New Categories
Edit the `taskCategory` select options in the HTML and update the category logic in JavaScript.

### Styling Modifications
All styles are contained in the `<style>` tag. Use CSS custom properties for easy theming.

### Feature Extensions
The codebase is modular and extensible. Add new features by following the existing patterns.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Your Name**
- Portfolio: [yourwebsite.com](https://yourwebsite.com)
- LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)
- Email: your.email@example.com

---

**Built with ❤️ using modern web technologies**