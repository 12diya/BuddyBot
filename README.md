# BuddyBot
A basic voice-activated desktop assistant developed in Python capable of doing many activities according to user directives.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

This Python script functions as a voice-activated desktop assistant, using the `pyttsx3` library for text-to-speech conversion, `speech_recognition` for voice input, and other libraries to execute diverse tasks. The assistant is capable of doing tasks such as querying Wikipedia, accessing web sites, displaying the current time, and initiating apps.

## Features

- Greet the user according to the time of day.
- Receive spoken instructions and transcribe them into written form.
- Conduct searches and review summaries from Wikipedia.
- Access YouTube videos according to user specifications.
- Launch a web browser and access Google, Stack Overflow, or LeetCode.
- Indicate the current time.
- Launch Visual Studio Code.

## Requirements

Before running the code, make sure you have the following Python libraries installed:

- `pyttsx3`
- `datetime`
- `speech_recognition`
- `wikipedia`
- `webbrowser`
- `pyautogui`
- `time`
- `os`
- `pywhatkit`
- `spotipy` (and Spotify authentication, if you plan to use it)

You can install these libraries using the following command:

```shell
pip install pyttsx3 datetime speech_recognition wikipedia webbrowser pyautogui pywhatkit spotipy
```

Please note that you might need to set up authentication for the Spotify functionality if you intend to use it.

## Usage

1. Run the Python script using a compatible Python interpreter.

```shell
python your_script.py
```

2. The assistant will greet you based on the time of day and wait for your voice command.

3. Speak your command clearly, and the assistant will attempt to perform the requested task.

4. The assistant can perform tasks such as searching Wikipedia, opening web pages, providing the current time, and opening Visual Studio Code.

5. To stop and exit the assistant, simply say "stop and exit."



---


