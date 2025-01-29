# AI-Enhanced Emotion-Based Subtitle Generator

## Overview
This project is an AI-powered subtitle generator that adds subtitles to a video based on detected emotions. The subtitles are displayed with a typing effect, and their colors change based on the detected emotion to enhance viewer experience.

## Features
- **Emotion Classification:** Uses a Naive Bayes classifier trained on sample subtitle data to classify emotions.
- **Typing Effect:** Subtitles appear on the screen gradually, mimicking a typing effect.
- **Emotion-Based Coloring:** Subtitle colors vary based on emotions (e.g., joy, sadness, anger, etc.).
- **Video Processing:** Processes video frames and overlays subtitles at appropriate timestamps.
- **Audio Integration:** Combines the processed video with the original audio for seamless playback.

## Technologies Used
- Python
- OpenCV (cv2)
- scikit-learn (Naive Bayes classifier, TF-IDF vectorizer)
- MoviePy
- NumPy

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/Emotion-based-Subtitle-generator.git
   cd Emotion-based-Subtitle-generator
   ```
2. Install dependencies:
   ```sh
   pip install numpy opencv-python scikit-learn moviepy
   ```
3. Place your video file in the project directory and update `video_path` in the script accordingly.

## Usage
Run the script to process a video and generate an output video with emotion-based subtitles:
```sh
python ai_emotion_subtitles.py
```

## Output
- A video file named `final_output_with_emotion_typing_effect.mp4` with subtitles added.
- A classification report of detected emotions.

## Future Enhancements
- Use a deep learning model for more accurate emotion classification.
- Support for multiple languages.
- Real-time subtitle generation.

## Contributing
Feel free to fork this repository and submit pull requests with improvements.

## Author
Sayak Mukherjee
