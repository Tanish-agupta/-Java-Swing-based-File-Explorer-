# 🗂️ Java File Explorer

A desktop-based **File Explorer** built using **Java Swing**. It replicates common file manager functionality such as navigation, directory structure browsing, file operations (open, delete), and history management (Back/Forward).

## ✨ Features

- 🧭 **Navigation Controls**
  - Back / Forward navigation
  - Up one directory
  - Refresh current directory
  - Go to Home directory

- 🌲 **Directory Tree View**
  - Expandable tree structure for browsing file systems
  - Lazy loading of directories for performance

- 📋 **File Table**
  - Sortable columns: name, type, size, and last modified
  - Icons for files and folders
  - Human-readable file sizes
  - Double-click to open files or enter directories

- 🗑 **File Deletion**
  - Multi-file selection and delete with confirmation

- 📂 **Address Bar**
  - Type a path to navigate directly

- 🖼️ **System Icons**
  - Uses system-native file and folder icons via `FileSystemView`

## 🚀 Getting Started

### Requirements

- Java 8 or higher
- Any Java IDE (IntelliJ, Eclipse, NetBeans) or command-line `javac`

### Run via IDE

1. Clone or download the project
2. Open `FileExplorer.java` in your IDE
3. Run the `main()` method

### Run via Command Line

```bash
javac FileExplorer.java
java FileExplorer

📁 Project Structure
└── FileExplorer.java   
└── README.md
