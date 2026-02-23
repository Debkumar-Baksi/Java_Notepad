# Java Notepad (AWT Based Text Editor)

## Overview
Java Notepad is a simple text editor built using Java AWT (Abstract Window Toolkit).  
It provides basic file handling and editing features similar to a minimal notepad application.

## Features

### File Menu
- New – Clears the text area
- Open – Opens an existing text file
- Save – Saves content to a text file
- Close – Exits the application

### Edit Menu
- Cut – Cuts selected text to clipboard
- Copy – Copies selected text to clipboard
- Paste – Pastes text from clipboard

## Technologies Used
- Java
- AWT (Abstract Window Toolkit)
- Java I/O Streams
- Java Clipboard API

## Project Structure
- Notepad.java – Main source file containing the complete implementation.

## How to Run

### 1. Compile the Program
```bash
javac Notepad.java
```

### 2. Run the Program
```bash
java Notepad
```

## Requirements
- Java JDK 8 or higher

## Functional Overview

### File Handling
- Uses `FileDialog` for selecting files.
- Uses `BufferedReader` and `FileReader` for reading files.
- Uses `DataOutputStream` and `FileOutputStream` for saving files.

### Clipboard Operations
- Uses `Toolkit.getSystemClipboard()`
- Uses `StringSelection` and `DataFlavor.stringFlavor`

## Known Limitations
- No font customization
- No undo/redo functionality
- Saves files in plain text format only

## Future Improvements
- Add Swing-based UI
- Add Undo/Redo support
- Add Font and Color customization
- Add keyboard shortcuts

## Author
Debkumar Baksi

---

## Video Demo

[Demo on LinkedIn](https://www.linkedin.com/posts/debkumar-baksi-269738279_java-javadeveloper-corejava-activity-7431732433559113728-Uluo?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEPrDnEBVjAz3BltRhVC2Ye2Hln8TZTZw70)
