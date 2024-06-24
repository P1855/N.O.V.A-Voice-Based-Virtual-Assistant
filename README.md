# **N.O.V.A : Voice-Based Virtual Assistant**
N.O.V.A, the voice-based virtual assistant,whose call name is **'Grapefruit'** combines NLP concepts with full-stack development. Its front end uses HTML, CSS, and JavaScript, while the Python-based backend handles logic and data processing. Nova’s customizable skills empower users to interact seamlessly through natural language commands. 

## CONTENTS

### -> front ( frontend )

1. **`inedx.html`** - This file contains all the elements for example buttons used in designing the User-Interface of the virtual assistant and this file also contains the incorporation of all other js and css files in it used for designing.
2. **`main.js`** - This file initializes text animations and a Siri-like waveform visualizer on document ready, and sets up event handlers for microphone button clicks, keyboard shortcuts, and input field changes to control assistant interactions and button visibility. It also includes functions to manage sending messages and toggling visibility of the mic and send buttons based on input field content.
3. **`scripts.js`** - This file contains the animation for the circular blob which rotates in the middle
4. **`style.css`** - This file has all the designing components in it for example the background color , the chatbox design and others.
5. **`controller.js`** - This file initializes the animation which happens when user clicks on any button on the UI.

### -> engine ( backend )

1. **`command.py`** - This file integrates text-to-speech and speech recognition with Eel for a web-based assistant. It processes voice commands, executes predefined tasks like opening applications or sending messages, and communicates with a web interface to display messages and receive input.
2. **`config.py`** - This file contains the ASSISTANT_NAME.
3. **`db.py`** - This Python file sets up an SQLite database with tables for system commands, web commands, and contacts. It includes commented-out code for inserting data and importing contacts from a CSV file into the database.
4. **`features.py`** - This file defines functions for a voice assistant, integrating SQLite for command lookup, playing YouTube videos, detecting hotwords, managing contacts, sending WhatsApp messages, initiating phone calls, and chatbot interactions using Hugging Face's HugChat API. This file also contains the hotword function which will the the hotword from the user's microphone and initiate the mic of the assistant. 
5. **`helper.py`** - This file containes functions which whill help in initiating other file

### -> `main.py` 

This Python file initializes the Eel web server, plays an assistant sound, and opens the web interface in *Microsoft Edge*.

### -> `run.py` 

This Python file uses multiprocessing to run two parallel processes: starting the Nova assistant and listening for a hotword activation.

### -> `device.bat`

This batch script disconnects old ADB connections, sets up a connected device for ADB over Wi-Fi, and connects to it. This file is used for connecting smartphone with the user device (desktop ) .


## FEATURES OF N.O.V.A 


- **Voice Commands** : Activate N.O.V.A with a simple hotword and let it handle your commands effortlessly. Whether it's opening applications, playing YouTube videos, or searching the web, N.O.V.A's voice recognition ensures seamless interaction.

- **Application Management** : Easily open any installed application or website by just mentioning its name. N.O.V.A can find and launch programs from a pre-defined list or even try to open unknown commands, making it incredibly versatile.

- **YouTube Integration** : Enjoy your favorite videos on YouTube without lifting a finger. Simply tell N.O.V.A what you want to watch, and it will handle the rest.

- **Hotword Detection** : Using advanced hotword detection technology, N.O.V.A listens for the call name "**grapefruit**" and springs into action, ready to assist you at a moment's notice.


https://github.com/P1855/N.O.V.A-Voice-Based-Virtual-Assistant/assets/98693127/8d6fe2b5-f2b2-4cd0-861c-223824becb72



- **Contact Management** : Find contacts and initiate phone calls or send messages effortlessly. N.O.V.A can search your contacts database and execute communication commands with ease.

- **WhatsApp Automation** : Send messages, make calls, or start video calls on WhatsApp through simple voice commands. N.O.V.A encodes and sends your messages, ensuring efficient and accurate communication.

- **Android Integration** : Automate tasks on your Android device, such as making calls or sending messages, directly from your assistant. N.O.V.A uses ADB commands to control your device and perform tasks hands-free.


https://github.com/P1855/N.O.V.A-Voice-Based-Virtual-Assistant/assets/98693127/a160cdd8-6551-4952-b7f9-7dc2476e4655


- **Conversational AI** : Engage in natural conversations with N.O.V.A's chatbot capabilities powered by Hugging Face's HugChat. Get responses to your queries, making interactions with N.O.V.A more human-like and intuitive.

- **Customizable Responses** : Enjoy a personalized experience as N.O.V.A speaks to you with a friendly voice, providing feedback and confirming actions, ensuring you are always in control.



https://github.com/P1855/N.O.V.A-Voice-Based-Virtual-Assistant/assets/98693127/1c9e7487-8214-4701-872b-9c18664f13e6

