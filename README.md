# Keylogger
A simple educational keylogger implementation in Python for authorized penetration testing and security research purposes. This project includes functionality to compile the Python script into a Windows executable using Nuitka.

## Description
This keylogger captures keyboard input and logs it to a text file. It's designed for educational purposes and authorized security testing scenarios where explicit permission has been obtained. The project supports creating standalone Windows executables for easier deployment.

## Features
- Real-time keystroke capture
- Logs both regular characters and special keys
- Simple text file output
- Cross-platform compatibility (optimized for Windows 11)
- Executable compilation support with Nuitka
- No console window when compiled (stealth mode)

## System Requirements
- **Operating System**: Windows 11 (tested), Windows 10, or other Windows versions
- **Python**: 3.9 (for development)
- **C++ Compiler**: Microsoft Visual C++ Build Tools (required for Nuitka)

## Installation

### Method 1: Clone from GitHub
git clone 'https://github.com/shivasaisandela2002/keylogger.git

### Change the directory
cd python-keylogger
### Run the command to install pynput 
pip install pynput

### Output
Keystrokes are logged to keylog.txt in the same directory, regular characters are logged as-is and special keys are logged in brackets (e.g., [space], [enter])


