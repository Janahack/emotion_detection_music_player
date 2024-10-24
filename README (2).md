
# Emotion Detection Music Player 🎵😄

## Overview
This project is an emotion detection-based music player. It analyzes a user's facial expression and mood, then plays music that matches the detected emotion.

## Features
- **Facial Emotion Detection**: Uses a camera to capture facial expressions and detect emotions (e.g., happy, sad, angry).
- **Music Recommendation**: Plays songs based on the detected mood.
- **Real-Time Detection**: Continuously monitors the user's emotions for real-time music adjustments.
- **User-Friendly Interface**: Easy to use with a simple, intuitive interface.

## Technology Stack
- **Programming Language**: Python
- **Libraries Used**: 
  - `OpenCV` for facial detection
  - `DeepFace` for emotion detection
  - `Pygame` for playing music
  
## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/emotion-detection-music-player.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the project:
   ```bash
   python app.py
   ```

## How It Works
- The application opens your webcam to detect your face and emotions.
- Based on the detected mood, it selects and plays appropriate music from the playlist.
  
## Future Improvements
- Adding more emotions to detect
- Expanding the music database with genre-based recommendations
- Mobile app integration

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
