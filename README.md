# Youtube Music Generator 🎵
Generate personalized YouTube Music tracks based on user moods using sentiment analysis and the ytmusicapi.

## Features
- **Mood Detection**: Uses AI-powered sentiment analysis to determine the user's mood from a text prompt.
- **Custom Track Selection**: Maps moods to track attributes (e.g., mood keywords) to fetch songs tailored to specific moods or activities.
- **Youtube Integration**: Fetches songs and provides direct URLs for playback in YouTube Music.

## Getting Started
Follow these instructions to set up and run the project locally.

  <img src="https://github.com/haileyplay/youtube-music-generator-mood/blob/main/Moodify_index.jpg" width="450" height="560">  <img src="https://github.com/haileyplay/youtube-music-generator-mood/blob/main/Moodify_songlist.jpg" width="450" height="560">

## Prerequisites
- Python 3.7 or higher.
- Install the ytmusicapi library.

## Usage
- Run the application and input a mood (e.g., "happy", "I am tired").
- The app will use sentiment analysis (by distilBART) to generate a mood-based query.
- Fetch songs tailored to the mood using YouTube Music's search functionality.
- Enjoy the music via the provided YouTube Music links.
