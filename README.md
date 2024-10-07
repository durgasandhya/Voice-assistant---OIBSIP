 Voice Assistant Project

Overview

This project is a Python-based Voice Assistant that interacts with users through voice commands and provides various functionalities, such as checking the current time, date, weather, sending emails, and web browsing. It utilizes speech recognition and text-to-speech technologies to enable real-time conversations and perform automated tasks based on user input.

 Features

- Speech Recognition: The assistant listens to voice commands and responds to the user's queries.
- Text-to-Speech: It provides verbal responses using Microsoft Zira voice.
- Weather Forecast: Fetches real-time weather updates using the OpenWeatherMap API for a specified location.
- Email Support: Allows the user to send emails by voice commands through Gmail SMTP.
- Search: Opens a web browser to perform internet searches based on user input.
- Open Applications: Can open specific applications such as Google and Spotify via voice commands.
- Time and Date Information: Provides the current time and date.
  
Technologies Used

- SpeechRecognition: To convert voice into text.
- Pyttsx3: For text-to-speech conversion.
- PyOWM: To retrieve weather data from the OpenWeatherMap API.
- Smtplib: To send emails through the Gmail SMTP server.
- Webbrowser: To open a web browser for search queries.
- Tkinter: For GUI (optional).

Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/voice-assistant.git
    ```

2. Install the required Python packages:
    ```bash
    pip install SpeechRecognition pyttsx3 pyowm smtplib
    ```

3. Configure the API Key and Email Credentials:
   - Open `main.py`, update the `API_KEY`, `EMAIL_ADDRESS`, and `EMAIL_PASSWORD` with your credentials.

4. Run the application:
    ```bash
    python main.py
    ```

 Usage

- Once the application starts, it will listen for your voice commands.
- You can say things like:
  - "What's the time?"
  - "What's the weather today?"
  - "Send email" (then provide recipient, subject, and body)
  - "Open Google"
  - "Bye" to terminate the assistant.

