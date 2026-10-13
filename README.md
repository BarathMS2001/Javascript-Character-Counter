Character Counter Web App
A simple and interactive character counter built using HTML, CSS, and JavaScript. The application allows users to type messages in a text area while displaying the current character count, remaining characters, and warning messages when the character limit is reached.

Features
Live character counting
Displays remaining characters
200-character input limit
Automatic input restriction after limit is reached
User-friendly warning message
Simple and clean interface
Built with pure HTML, CSS, and JavaScript
Preview
The application contains:

A message input box
Real-time character counter
Remaining character display
Character limit warning message
Example:

125/200 characters (75 remaining)
When the limit is reached:

200/200 characters (0 remaining)
Character limit reached!
Technologies Used
HTML5
CSS3
JavaScript (ES6)
Project Structure
character-counter-webapp/
│
├── index.html
├── images/
│   └── finalimage.jpg
└── README.md
How It Works
The user enters text into the message box.
JavaScript listens for the input event.
The current character count is calculated.
Remaining characters are displayed dynamically.
If the user exceeds 200 characters:
Extra characters are automatically removed.
A warning message is displayed.
Key JavaScript Logic
counter.textContent =
`${currentLength}/${maxChars} characters (${remaining} remaining)`;
Example:

If:

currentLength = 50;
maxChars = 200;
remaining = 150;
The displayed output becomes:

50/200 characters (150 remaining)
