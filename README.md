# Iris - Your Virtual Assistant

## Description
Iris is your virtual assistant, designed to make life easier by performing a variety of tasks. Whether you’re at work or home, Iris can help you stay organized and get information quickly.

## Who is Iris For?
Iris is designed for a wide range of users:
- **Students**: A great tool for staying organized, finding quick information, and managing tasks.
- **Adults**: Perfect for managing day-to-day tasks and organizing information all within a single app.

With a simple design and intuitive interface, anyone can get started with Iris.

## Features
Iris currently supports the following features:
- **Quick Search**: Get quick answers or relevant links. Simply type a message, and Iris will respond with information or useful links.
- **Link Handling**: Enter a link in chat, and Iris will open it directly for you.
- **To-Do List**: Keep track of tasks and stay organized.
- **Notes**: Store notes for easy access.
- **Timer**: Set a timer for tasks or reminders.
- **Personalization**: Set your nickname and location (location helps with providing weather forecasts). Alternatively, type "weather in [city]" to get a forecast without setting a location.
- **Voice Commands**: Use the wake word "Iris" or press the microphone button to speak your commands directly.

The chat window is also collapsible; click the chat button to toggle its visibility.

## Usage

To use this project, follow these steps:

1. **Open the Project Folder**:
   - **Option 1**: Open the folder in an IDE (like VS Code or PyCharm).
   - **Option 2**: Open a terminal or command prompt, navigate to the folder containing the project files, and ensure you have all required libraries installed.

2. **Run the Project**:
   - After ensuring the dependencies are installed, you can start the project by running the main Python file.
   - For example, in a terminal, run:
     ```bash
     python main.py
     ```

## Libraries Used and Installation

This project relies on several libraries for its functionality. Ensure you have the following libraries installed:

- **Python Standard Libraries**:
  - `sys`, `os`, `subprocess`, `time`, `threading`

- **External Libraries**:
  - `PyQt5` (for GUI elements)
  - `sqlite3` (for database interactions)
  - `googlesearch-python` (for performing Google searches)
  - `webbrowser` (to open links in a browser)
  - `urllib.parse` (for URL handling)
  - `speech_recognition` (for voice input)
  - `requests` (for making HTTP requests)
  - `beautifulsoup4` (for web scraping)

### Installation Instructions

To install the necessary libraries, open a terminal or command prompt and run the following commands:

## macOS and Windows:
### Install all libraries at once
pip install PyQt5 googlesearch-python speechrecognition requests beautifulsoup4

### Run the file
Run the file from your terminal but going into the folder and typing "python IRIS".
Alternatively, run the file from an IDE environemnt by opening the folder, don't forget to install libraries.

This will install all required libraries for the project.

## Using the Microphone
Iris can recognize the wake word "Iris." When you say the wake word, Iris listens for your command, displays it in the chat window, and responds accordingly. You can also click the microphone button to ask your questions.

## Language Support
Iris can interact in different languages! Go to **User Information and Customization** in the menu to set your preferred language, which will change the chat window language and enable voice commands in that language as well.

## Thank You
Thank you for using Iris, your versatile virtual assistant!


