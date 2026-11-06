# JARVIS-no-click-bait-cuz-others-sucks
i made jarvis using only open source tools cuz most of them are paid i only paid for gemini cuz it cheap and used claude haiku enjoy
#What You Need Before Starting:
Windows 10 or 11 (He uses Windows-specific APIs to hook into the OS).
Python 3.10+ installed on your system (make sure to check "Add Python to PATH" during installation).
A free Groq API Key (Get one at console.groq.com).
#instalation:
Installation & Setup (It's easy)
I made .bat files so you don't have to mess around in the terminal for an hour.
Download the code: Clone this repo or download it as a ZIP and extract it to a folder.
Run the Setup: Double-click the setup.bat file. This will automatically create a virtual environment, install all the necessary Python libraries (pyautogui, playwright, opencv, etc.), and set up the local databases.
Add your API Keys: The setup script will either prompt you, or you can just open the .env file it creates (look at .env.example if you're confused) and paste your Groq API key in there.
#How to Start JARVIS:
Once setup is done, you don't need to open the terminal anymore.
Just double-click the JARVIS Desktop Shortcut (or run run_jarvis.bat / jarvis.py).
To talk: Hold down the Right Ctrl key, speak your command, and release it.
Emergency Stop: If he's moving your mouse or typing and you want him to stop immediately, press Ctrl + Alt + Shift + X.
Known Quirks
Sometimes Windows Defender gets nervous about Python scripts controlling the mouse. You might need to allow it.
If he mishears you (e.g., you say "dz exam" and he hears "zed exams"), he should ask you to clarify, but speaking clearly helps.
Feel free to fork this, submit pull requests, or break it entirely. Enjoy having your own JARVIS!
