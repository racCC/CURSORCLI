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


## 🎯 Examples

### Creating a Complete To-Do App

```bash
npm start
> "Create a to-do list in HTML"
```
### Adding Features to Existing Projects

```bash
> "edit the todo app to add dark mode"
```

**Result**:
- ✅ Dark mode feature added
- ✅ Project automatically relaunched
- ✅ Changes visible immediately

---

**Made with ❤️ by Rachit Pednekar and AI**

Transform your ideas into reality with CURSORCLI! 🚀 
