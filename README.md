# INSTAGRAM-BOT-MESSENGER-VERSION-0.1



Instagram Bot Messenger
Description
Instagram Bot Messenger is a program designed for automating message sending via Instagram, developed using the Kivy framework. The program allows users to easily configure and run a bot for sending messages, providing an intuitive user interface with options for file selection, text input, delay settings, and maximum message count.

Features
Cross-Platform: The application operates on Android, Windows, Linux, and iOS, making it accessible across various devices.
Multi-functional Interface: The app interface allows users to input login credentials, password, message content, select files, specify delays between messages, and set a maximum message count.
Language Support: Supports English and Ukrainian languages, with easy language switching through a dialog window.
API Key Validation: A mechanism for validating Instagram API keys, with notifications for successful or unsuccessful verification.
File Selection: An interface for selecting files (images, videos, audio), with the ability to view and choose files for sending.
Start and Stop Sending: Buttons for starting and stopping the message sending process, as well as resetting all input fields.
Updates: Functionality for checking bot updates and notifying about update status.
User Interface Interaction: Dialog windows for text input, file selection confirmation, and API key entry, ensuring ease of use.
How It Works
Interface: The main interface of the app includes fields for entering login details, password, message content, delay between messages, and maximum message count. There is also a field for entering a list of usernames and a button for file selection.

File Selection: Users can select files for sending through the file chooser window, where they can view and mark files for sending.

API Key: To use the bot, an Instagram API key must be entered and validated through a dedicated dialog window.

Start and Stop: The "Start" and "Stop" buttons allow users to begin and halt the message sending process. During sending, the bot simulates delays between messages and updates status.

Updates: The application can check for updates and notify about successful updates or errors.

Language: The interface language can be switched between English and Ukrainian via the language selection menu.

Installation and Usage
For Windows
Download and extract the latest version of the application from GitHub Releases.
Run InstagramBotMessenger.exe.
For Android
Build the APK file using Buildozer:
bash
Копіювати код
buildozer -v android debug
Install the APK on your Android device.
For Linux
Download and extract the latest version of the application from GitHub Releases.
Run InstagramBotMessenger.
For iOS
Use Xcode to create an iOS build based on your project.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contributing
Contributions to the project are welcome. If you find bugs or have suggestions for improvements, please create a pull request or open an issue.


