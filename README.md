# Lana - Your Intelligent Voice Assistant

Welcome to Lana, a sophisticated and versatile voice assistant built using Python. Lana is designed to provide you with a hands-free, intuitive way to interact with your computer, offering a range of functionalities from web searches and news updates to music playback and application control.

## Project Overview

Lana aims to create a seamless and efficient user experience by leveraging voice commands to perform various tasks. This project emphasizes user-friendliness, extensibility, and robustness, making it a valuable tool for everyday use.

## Features

* **Voice-Controlled Interaction:**
    * Interact with your computer using natural language voice commands.
    * Trigger word activation ("Lana") for seamless operation.
    * Continuous listening mode (optional) for uninterrupted interaction.
* **Web Automation:**
    * Perform Google searches and retrieve search result links.
    * Open websites directly using voice commands.
    * Automate web-based tasks using Selenium.
* **Information Retrieval:**
    * Retrieve summaries from Wikipedia.
    * Get real-time news headlines.
    * Fetch accurate weather information.
* **Multimedia Control:**
    * Play music on YouTube through voice commands.
* **System Integration:**
    * Open applications using voice commands.
    * Retrieve current time, date, and day.
* **Entertainment:**
    * Tell jokes using the `pyjokes` library.
* **Conversational Abilities:**
    * Engage in basic conversational exchanges.
    * Provide simple recipe and nutrition information.
* **Error Logging:**
    * Robust error logging using the python logging library, that will record all the errors in the lana.log file.

## Why These Libraries?

The choice of libraries in Lana was driven by the need for functionality, reliability, and ease of use. Here's a breakdown:

* **`speech_recognition (sr)`:**
    * This library provides a simple and effective way to convert speech to text.
    * It supports multiple speech recognition engines, including Google Web Speech API, which offers excellent accuracy.
    * It handles microphone input and ambient noise adjustment.
* **`pyttsx3`:**
    * A cross-platform text-to-speech library that works offline.
    * It offers a wide range of voice options and allows customization of speech rate and volume.
    * It's efficient and easy to integrate.
* **`pywhatkit`:**
    * Simplifies the process of playing YouTube videos.
    * It provides a convenient way to integrate multimedia functionality.
    * It also has other useful functions.
* **`wikipedia`:**
    * Provides a straightforward way to access Wikipedia summaries.
    * It handles disambiguation and page errors.
    * It allows quick retrieval of information.
* **`pyjokes`:**
    * A lightweight library for generating random jokes.
    * It adds an element of entertainment to the assistant.
* **`requests`:**
    * A powerful and user-friendly library for making HTTP requests.
    * It's used to fetch news data from the News API.
    * It is very reliable.
* **`aiohttp`:**
    * An asynchronous HTTP client/server library.
    * It's used for efficient and non-blocking weather data retrieval.
    * It is very fast.
* **`selenium`:**
    * A powerful tool for automating web browsers.
    * It's used for Google searches and web automation tasks.
    * It is very robust for web scraping.
* **`webdriver_manager`:**
    * This library helps to manage the chrome web driver.
    * It automatically downloads and install the correct driver for the current chrome version.
* **`datetime`:**
    * A built-in Python module for working with dates and times.
    * It's used to retrieve current time, date, and day.
* **`os`:**
    * A built-in python module for interacting with the operating system.
    * This is used to open applications.
* **`logging`:**
    * A built-in python module for logging errors and other information.
    * It allows to create a log file that will contain all the errors that the program encountered.

## Prerequisites

Before running Lana, ensure you have the following installed:

* Python 3.x
* pip (Python package installer)
* Google Chrome (for Selenium)

Install the required Python libraries using pip:

```bash
pip install SpeechRecognition pyttsx3 pywhatkit wikipedia pyjokes requests aiohttp selenium webdriver_manager
