# 🚀 CURSORCLI - AI-Powered Project Generator

A powerful command-line interface that uses AI to instantly create, launch, and manage web applications and projects. Turn your ideas into working applications with a single command!

## ✨ Features

### 🎯 **Instant Project Creation**
- Create complete web applications with one command
- AI-powered project generation using Gemini API
- Automatic file structure and content generation
- Support for HTML, CSS, JavaScript, Python, React, and more

### 🚀 **Automatic Launch**
- Projects launch automatically after creation
- Local server setup with browser opening
- Smart project type detection and appropriate server configuration

### 🛠️ **Project Management**
- List all created projects
- Delete individual projects or all projects
- Edit existing projects with natural language commands
- Update and fix issues in existing projects

### 🎨 **Enhanced User Experience**
- Beautiful terminal UI with colors and animations
- Progress indicators and success messages
- Comprehensive help system
- Error handling and fallback mechanisms

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- Python (for HTML server fallback)
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/CURSORCLI.git
   cd CURSORCLI
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory:
   ```env
   GEMINI_API_KEY=your_gemini_api_key_here
   ```

4. **Build the project**
   ```bash
   npm run build
   ```

5. **Start the CLI**
   ```bash
   npm start
   ```

## 📖 Usage

### Creating Projects

```bash
# Create a to-do list application
"Create a to-do list in HTML"

# Create a calculator
"Create a calculator in HTML"

# Create a weather app
"Create a weather application"

# Create a Python script
"Write a Python script for a calculator"
```

### Managing Projects

```bash
# List all projects
list

# Delete a specific project
delete todo-app

# Delete all projects (with confirmation)
delete all

# Show help
help
```

### Editing Projects

```bash
# Fix issues
"css file is not working"

# Add features
"edit the calculator to add dark mode"

# Modify styling
"modify the styling in weather app"

# Add new functionality
"add a search feature to todo-app"
```

### Running Projects

```bash
# Run a project
"run the project"

# Execute a specific project
"execute the python script"
```

## 🏗️ Project Structure

```
CURSORCLI/
├── src/
│   └── index.ts          # Main CLI application
├── code/                 # Generated projects directory
├── dist/                 # Compiled JavaScript
├── package.json          # Dependencies and scripts
├── tsconfig.json         # TypeScript configuration
└── README.md            # This file
```

## 🔧 Configuration

### Environment Variables

- `GEMINI_API_KEY`: Your Gemini API key for AI-powered project generation

### Project Types Supported

- **HTML/CSS/JS**: Static web applications
- **Python**: Scripts and applications
- **React**: React applications with npm
- **Node.js**: Express servers and APIs
- **Custom**: Any project type the AI can generate

## 🎯 Examples

### Creating a Complete To-Do App

```bash
npm start
> "Create a to-do list in HTML"
```

**Result**: 
- ✅ Complete to-do app with HTML, CSS, and JavaScript
- ✅ Automatic server launch at http://localhost:8000
- ✅ Browser opens automatically
- ✅ Ready to use immediately

### Adding Features to Existing Projects

```bash
> "edit the todo app to add dark mode"
```

**Result**:
- ✅ Dark mode feature added
- ✅ Project automatically relaunched
- ✅ Changes visible immediately

## 🛠️ Development

### Building from Source

```bash
# Install dependencies
npm install

# Build TypeScript
npm run build

# Run in development mode
npm run dev
```

### Available Scripts

- `npm start`: Start the CLI application
- `npm run build`: Build TypeScript to JavaScript
- `npm run dev`: Run with nodemon for development

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Google Gemini API** for AI-powered project generation
- **Node.js** and **TypeScript** for the development platform
- **Chalk** for beautiful terminal output
- **Express** and **http-server** for local development servers

## 🐛 Issues and Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/yourusername/CURSORCLI/issues) page
2. Create a new issue with detailed information
3. Include your Node.js version and operating system

## 📈 Roadmap

- [ ] Support for more project types (Vue, Angular, etc.)
- [ ] Database integration
- [ ] Deployment options (Vercel, Netlify, etc.)
- [ ] Project templates
- [ ] Collaboration features
- [ ] Plugin system

---

**Made with ❤️ by [Your Name]**

Transform your ideas into reality with CURSORCLI! 🚀 