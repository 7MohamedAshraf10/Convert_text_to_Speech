# Convert_text_to_Speech Python Project


This is a Python project that allows you to convert text into speech using various text-to-speech (TTS) engines. It provides a simple and user-friendly interface to convert your textual content into spoken words. Whether you're looking to create audiobooks, accessibility features, or simply have some fun with text-to-speech technology, this project has got you covered!

## Features

- **Multiple TTS Engines**: This project supports multiple text-to-speech engines, allowing you to choose the one that suits your preferences or needs.

- **Customization Options**: You can customize aspects of the generated speech, such as voice pitch, rate, volume, and more, depending on the chosen TTS engine.

- **Save as Audio**: You can save the generated speech as audio files in various formats, making it convenient for offline use or sharing.

## Supported TTS Engines

1. **Google Text-to-Speech**: Utilizes Google's TTS technology to generate high-quality speech.

2. **Microsoft Azure Text-to-Speech**: Connects to the Azure TTS service for natural and expressive speech synthesis.

3. **Amazon Polly**: Interacts with Amazon's Polly service to generate lifelike speech.

## Installation

Before you start using this project, you need to install the necessary dependencies, including the Tesseract OCR engine for text recognition. Follow the steps below to install Tesseract:

### Installing Tesseract

1. **Windows**:

   - Download the Tesseract installer for Windows from the [Tesseract GitHub repository](https://github.com/tesseract-ocr/tesseract).
   - Run the installer and follow the installation instructions.
   - Make sure to add the Tesseract installation directory to your system's PATH variable.

2. **macOS**:

   - Install Tesseract using Homebrew by running the following command in your terminal:
     ```
     brew install tesseract
     ```

3. **Linux**:

   - On Debian-based systems (e.g., Ubuntu):
     ```
     sudo apt-get install tesseract-ocr
     ```

   - On Red Hat-based systems (e.g., Fedora):
     ```
     sudo yum install tesseract
     ```

4. **Python Dependencies**:

   After installing Tesseract, you can install the required Python dependencies using pip:
   ```
   pip install -r requirements.txt
   ```
