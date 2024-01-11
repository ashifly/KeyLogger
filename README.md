## 🔐 Keylogger with Remote Posting 🌐

A Python script using `pynput` to log keystrokes and send data to a remote server periodically. Designed for educational purposes, use responsibly with consent.

### Dependencies 📦
- **pynput**: Monitors keyboard inputs.
- **requests**: Sends HTTP POST requests.
- **json**: Converts Python objects to JSON.
- **threading**: Sets up a timer for regular server posts.

### How it Works 🛠️
1. Captures keyboard inputs with `pynput`, logging in `text`.
2. Handles special cases for Enter, Tab, Space, Backspace, Shift, Ctrl, and Esc keys.
3. Timer function (`send_post_req`) periodically sends keystrokes to the server as JSON.
4. Configurable server address, port, and post interval.
5. Runs indefinitely, continuously capturing and posting keystrokes.

### Configuration ⚙️
- **ip_address**: Set the server's IP.
- **port_number**: Set the server port.
- **time_interval**: Set post interval (seconds).

### Usage 🚀
1. Install dependencies: `pip install pynput requests`.
2. Configure server details and interval.
3. Run the script to capture and post keystrokes.

### Disclaimer ⚠️
Educational use only. Unauthorized distribution may violate privacy and laws. Use responsibly with consent.

### Note 📝
Exercise caution and consider ethical/legal implications associated with keylogging.
