# 🚀 CURSORCLI - AI-Powered Project Generator

A powerful command-line interface that uses AI to instantly create, launch, and manage web applications and projects. Turn your ideas into working applications with a single command!

## ✨ Features

### 🎯 **Instant Project Creation**
-Create HTML, Python, React, Node apps via Gemini AI

### 🚀 **Automatic Launch**
-Projects open in your browser right after creation

### 🛠️ **Project Management**
-Edit, delete, fix, and upgrade with simple commands

### 🎨 **Enhanced User Experience**
-Colorful UI, progress indicators, and helpful errors

## 🚀 Quick Start

### Prerequisites
-Node.js (v14+), npm/yarn, Python, Git

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
"Create a to-do list in HTML"
"Create a calculator in HTML"
# List all projects
list
# Delete a specific project
delete todo-app
# Delete all projects (with confirmation)
delete all
# Show help
help
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




---

**Made with ❤️ by Rachit Pednekar and AI**

Transform your ideas into reality with CURSORCLI! 🚀 
