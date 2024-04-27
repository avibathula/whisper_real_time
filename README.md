# Real Time Whisper Transcription

![Demo gif](demo.gif)

This is a demo of real time speech to text with OpenAI's Whisper model. It works by constantly recording audio in a thread and concatenating the raw bytes over multiple recordings.

## Updated installation

The project has been updated to use poetry.

`PyAudio` package has a dependency on `PortAudio` library, So, we need to
install the `PortAudio` library on your Mac. You can do this using the Homebrew
package manager with the following command:
```
brew install portaudio
```

Then, to install dependencies simply run
```
poetry install
```

Reference: see [original installation info](original_installation.md)
