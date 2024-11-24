# Keylogger Python Tool

## Description
This Python tool logs keystrokes to a file. It uses the `pynput` library to listen for key events and records each key press, including alphanumeric characters and special keys like space and enter. The logged keys are saved to a file named `keylog.txt` for further analysis.

**Note**: This tool is intended for educational and ethical use only. Be sure to obtain proper consent if you use this tool in any environment. Unauthorized use may violate privacy laws.

## Features
- Logs alphanumeric characters and special keys.
- Writes keystrokes to a `keylog.txt` file.
- Captures special keys like space, enter, etc.
- Can be stopped by pressing `Ctrl+C`.

## Installation

1. Ensure you have Python 3.x installed on your machine.
2. Install the required dependencies:

   ```bash
   pip install pynput
git clone https://github.com/yourusername/keylogger.git
cd keylogger
python keylogger.py
Keylogger started. Press Ctrl+C to stop.
h[e]l[l]o[space]w[o]r[l]d[enter]
