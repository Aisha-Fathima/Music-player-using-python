# Python Music Player 🎵
 A simple command-line music player built with Python using the `pygame.mixer` module. This project allows you to list and play songs from a specific directory, and control playback with commands like `pause`, `play`, and `stop`. Supports `.mp3` and `.wav` file formats. Perfect for learning basic Python audio handling!

## Features
List songs from a specified directory.
Play, pause, unpause, and stop music using text commands.
Command-line interface for interaction.
Supports .mp3 and .wav file formats.
Simple and intuitive user input control for managing playback.

## Requirements
Python 3.x
Pygame library

## Setup and Installation
1.Clone the repository:

   git clone https://github.com/Aisha-Fathima/Music-player-using-python.git
   cd python-music-player 

2.Install the pygame module if you haven't already:

   pip install pygame

3.Update the music_dir variable in the script to match the directory containing your music files:

  music_dir = "/path/to/your/music/folder"

4.Run the program:

python music_player.py


## How to Use
The script will list all music files (.mp3 and .wav) in the specified directory.
You can select a song by entering its corresponding number.
Once a song is playing, use the following commands:
-play to resume a paused song.
-pause to pause the song.
-stop to stop the song and choose another one.
-exit to exit the player.

## Example
```
Current directory: /home/abcd/Music

Available Songs:
0 - song1.mp3
1 - song2.wav
2 - song3.mp3

Enter song number to play (or -1 to exit): 1
Now playing: song2.wav

Enter command (play, pause, stop, exit): pause
    Paused. Enter 'play' to resume.
    
Enter command (play, pause, stop, exit): play
    Resumed.

Enter command (play, pause, stop, exit): stop
Song stopped.

Available Songs:
0 - song1.mp3
1 - song2.wav
2 - song3.mp3

Enter song number to play (or -1 to exit): -1
Exiting the music player.


```

## Future Enhancements
-Add a graphical user interface (GUI) for easier control.
-Add support for additional audio formats.
-Implement a playlist feature for continuous music playback.

