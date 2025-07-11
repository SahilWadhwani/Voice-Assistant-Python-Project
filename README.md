# Voice Assistant (Python)

A beginner-friendly desktop voice assistant built with Python that performs everyday tasks using voice commands

This virtual assistant can greet you, answer queries via Wikipedia, open websites, play music, tell the current time, launch applications, and even send emails — all through your voice.

---

##  Features

-  **Voice Command Recognition** (SpeechRecognition)
-  **Text-to-Speech** using `pyttsx3`
-  **Wikipedia Search & Voice Summary**
-  **Open websites** like Google & YouTube
-  **Play music** from your local directory
-  **Speak the current system time**
-  **Launch VS Code** or other local applications
-  **Send emails** through voice input (SMTP)

---

##  Tech Stack

| Functionality        | Library / Tool           |
|----------------------|--------------------------|
| Voice Input          | `speech_recognition`     |
| Text-to-Speech       | `pyttsx3`                |
| Knowledge Queries    | `wikipedia`              |
| Task Automation      | `os`, `webbrowser`       |
| Email Sending        | `smtplib`                |
| Time Management      | `datetime`               |

---

##  Setup & Installation

1.  **Clone the repo:**
    ```bash
    git clone (https://github.com/SahilWadhwani/Voice-Assistant-Python-Project.git)
    ```

2.  **Install dependencies:**
    Make sure Python 3.x is installed.
    ```bash
    pip install pyttsx3 SpeechRecognition wikipedia pyaudio
    ```
     **If `pyaudio` fails on Windows:**
    ```bash
    pip install pipwin
    pipwin install pyaudio
    ```

---

##  Usage

1.  Open `main.py` in your IDE.
2.  Run the script:
    ```bash
    python main.py
    ```
3.  Speak a command when prompted, such as:
    * “Wikipedia Elon Musk”
    * “Open YouTube”
    * “Play music”
    * “What’s the time”
    * “Email to name”

---

##  Security Notes

For email functionality, you must enable “Less secure apps” in Gmail (not recommended) or use [App Passwords](https://support.google.com/accounts/answer/185833?hl=en) if 2FA is enabled.

**Remember to replace placeholders** in the `main.py` file with your specific details:
* Your music directory path
* Your email and password
* Recipient email address

---

##  File Structure

│
├── main.py                 # Main script file
├── README.md               # Project documentation


---

##  Future Improvements

* Add voice-controlled weather updates using an API.
* Integrate OpenAI for smarter conversations.
* Add error handling for more stability.
* Implement random song selection from the playlist.

---

##  Connect with Me

Feel free to reach out on [LinkedIn](https://www.linkedin.com/in/sahil-wadhwani-06848122a/) or check out more of my work 
