# 🌐 Live Voice Language Translation 🌐

![Project Logo](https://www.addevice.io/storage/ckeditor/uploads/images/637ba6f15f60e_how.to.create.a.voice.translation.app.1920.1080.1.png)

🚀 **Live Voice Language Translation** is a real-time voice translation application that translates spoken language into a user-selected language, displaying the text on a screen and also playing the translated audio. This project is developed using Python with Flask for the backend and HTML, CSS, and JavaScript for the frontend.

## ✨ Features

- 🎤 **Real-time Voice Translation**: Translate spoken language into over 20 different languages.
- 📄 **Text Display**: View translated text on the screen.
- 🔊 **Audio Output**: Hear the translation spoken out loud.
- ⏲ **Dynamic UI**: Interactive user interface with popup notifications and button animations.

## 📹 Demo Video

[![Live Translation Demo](https://img.youtube.com/vi/wqHIiMX3V-U/maxresdefault.jpg)](https://www.youtube.com/watch?v=wqHIiMX3V-U)


## 📖 How It Works

1. **User selects source and target languages** from the dropdown menus.
2. **User uploads an audio file** or clicks the "Listen" button to start live translation.
3. The application **processes the audio**, translates the text, and displays the translated text on the screen.
4. The translated text is **spoken out loud** using text-to-speech.

## 🧑‍💻 Contributing

We welcome contributions! Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting a pull request.


## 🌟 Acknowledgements

- [Google Speech Recognition API](https://cloud.google.com/speech-to-text)
- [Google Translate](https://translate.google.com/)
- [gTTS (Google Text-to-Speech)](https://pypi.org/project/gTTS/)

## 📞 Contact

For any inquiries, please contact [Nithin Rajulapati](mailto:nithinrajulapati9999@gmail.com).

## 🛠️ Setup Instructions

Follow these steps to set up and run the project locally.

### Prerequisites

Make sure you have the following installed:

- Python 3.6+
- Flask
- `ffmpeg` (for audio processing)

### Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/Nani1-glitch/live-voice-translation.git
    cd live-voice-translation
    ```

2. **Install Dependencies**

    ```bash
    pip install -r requirements.txt
    brew install ffmpeg
    ```

### Running the Application

1. **Start the Flask Server**

    ```bash
    python app.py
    ```

2. **Open in Browser**

    Open your web browser and go to `http://127.0.0.1:5000`.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

<div align="center">
    Made with ❤️ by [Nithin Rajulapati](https://github.com/Nani1-glitch)
</div>


### Project Structure

```plaintext
live-voice-translation/
├── app.py               # Flask application
├── requirements.txt     # Python dependencies
├── static/
│   ├── styles.css       # CSS for styling
│   └── scripts.js       # JavaScript for interaction
├── templates/
│   └── index.html       # HTML template
└── README.md            # Project README

