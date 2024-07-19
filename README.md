# Generate Subtitle

This script follows instructions from [DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-generate-and-add-subtitles-to-videos-using-python-openai-whisper-and-ffmpeg). It will to generate subtitles from a video file.

Other references:

- [GitHub - SYSTRAN/faster-whisper: Faster Whisper transcription with CTranslate2](https://github.com/SYSTRAN/faster-whisper)
- [ffmpeg — Homebrew Formulae](https://formulae.brew.sh/formula/ffmpeg)
- [GitHub - openai/whisper: Robust Speech Recognition via Large-Scale Weak Supervision](https://github.com/openai/whisper)

## Installation

```bash
brew install ffmpeg
pip3 install -r requirements.txt
```

## Usage

Change `input_video = "/Users/hieple/Movies/2024-07-18 20-32-42.mov"` to the path to your video file.

```bash
python3 main.py
```

## License

MIT
