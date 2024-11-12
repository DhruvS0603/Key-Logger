# Key-Logger
This project is a basic keylogger implemented in HTML, CSS, and JavaScript. It captures and logs keypress events in the browser, displaying each pressed key and its state (pressed or released) in real-time.<br><br>

Features<br>
Start and Stop Key Logging: Buttons to start and stop logging keypresses.<br>
Display Key Information: Displays the name of the key being pressed and its state ("Key is down" or "Key is up").<br>
Styled UI: Simple interface with a styled title, logging area, and controls.<br><br>
Files<br>
keylogger.html: HTML structure and layout for the project interface, including buttons, key log display, and basic styling.<br>
keylogger.js: JavaScript functionality for handling keypress events and updating the UI in real-time.<br><br>
Usage<br>
Open keylogger.html in a browser.<br>
Click Start Logging Keypresses to begin capturing key events.<br>
The key name and its state (up or down) will be displayed as keys are pressed.<br>
Click Stop Logging Keypresses to stop the logging process.<br><br>
Implementation Details<br>
The Start button activates event listeners for keydown and keyup events.<br>
The Stop button removes these event listeners and clears the log display.<br>
Real-time updates are shown by modifying the text content of #log and #state elements.<br><br>
Styling<br>
The UI uses basic CSS to structure and style the layout, providing a clear and readable interface for displaying keypress information.<br>