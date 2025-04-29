# Keylogger

This is a simple keylogger project built with Python using the `pynput` library for listening to keyboard events. The keylogger captures keypresses, key releases, and key holds, saving the events to both a plain text file and a JSON file for structured logging.

## Features:
- **Key Capture**: Logs pressed, held, and released keys.
- **Text Log**: Captures the keypresses in a sequential manner and saves them to `keylogger.txt`.
- **JSON Log**: Logs key events in a structured format to `key_log.json`.
- **GUI**: Simple interface using `tkinter` to start and stop the keylogger.

## Technologies Used:
- **Python**: Programming language.
- **pynput**: For detecting keyboard input.
- **tkinter**: For the GUI interface.
- **JSON**: For structured logging of key events.

## Installation:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/keylogger.git
    ```

2. Install dependencies:
    ```bash
    pip install pynput
    ```

3. Run the Python script:
    ```bash
    python keylogger.py
    ```

## How It Works:
1. **Start the Keylogger**: The user can start the keylogger by clicking the "Start" button on the GUI.
2. **Key Logging**: The keylogger records the keys pressed, held, and released, and saves the data in both `keylogger.txt` and `key_log.json`.
3. **Stop the Keylogger**: The keylogger can be stopped by clicking the "Stop" button.

## Output:
- `keylogger.txt`: Contains the raw sequence of key events.
- `key_log.json`: A structured JSON file storing pressed, held, and released key events.

## Important Note:
This keylogger is for educational purposes only. Please use it responsibly and make sure to obtain proper consent before recording any keystrokes.


