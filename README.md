# Convert_text_to_Speech Python Project

![Project Logo](project_logo.png)

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

## Usage

1. Clone this GitHub repository and navigate to the project directory:
   ```
   git clone https://github.com/your-username/Convert_text_to_Speech.git
   cd Convert_text_to_Speech
   ```

2. Run the Python script:
   ```
   python convert_text_to_speech.py
   ```

3. Follow the on-screen instructions to input the text you want to convert and select the desired TTS engine and customization options.

4. Enjoy the generated speech! You can listen to it directly or save it as an audio file.

## Contributing

If you'd like to contribute to this project, feel free to open issues or submit pull requests on the [GitHub repository](https://github.com/your-username/Convert_text_to_Speech). Your feedback and contributions are highly appreciated!

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to reach out to us with any questions, suggestions, or feedback. Happy text-to-speech converting!
