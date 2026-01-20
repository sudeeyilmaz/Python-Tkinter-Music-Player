# 🎵 Python Desktop Music Player

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Tkinter](https://img.shields.io/badge/Tkinter-GUI-green)
![Pygame](https://img.shields.io/badge/Pygame-Audio-red)

A simple yet functional **MP3 Music Player** application developed using **Python**. It features a graphical user interface (GUI) built with **Tkinter** and handles audio playback using the **Pygame Mixer** module.

## 🚀 Features

* **Playlist Management:** Automatically scans a specified directory for `.mp3` files and lists them.
* **Playback Controls:** Includes graphical buttons for **Play, Pause, Stop, Next,** and **Previous**.
* **Real-time Feedback:** Highlights the currently playing song in the list and displays the track name.
* **Custom UI:** Uses a dark-themed interface with custom icons for control buttons.

## 🛠️ Tech Stack

* **Language:** Python
* **GUI Framework:** Tkinter (Standard Python Interface)
* **Audio Engine:** Pygame (Mixer module)
* **OS Interaction:** `os` & `fnmatch` modules for file handling.

## 📂 Project Structure

```text
├── main.py             # The main source code
├── play_img.png        # Asset: Play button icon
├── pause_img.png       # Asset: Pause button icon
├── stop_img.png        # Asset: Stop button icon
├── next_img.png        # Asset: Next button icon
├── prev_img.png        # Asset: Previous button icon
└── README.md           # Documentation
## ⚙️ Installation & Usage
1. Clone the repository
Bash

git clone [https://github.com/sudeeyilmaz/Python-Tkinter-Music-Player.git](https://github.com/sudeeyilmaz/Python-Tkinter-Music-Player.git)
cd Python-Tkinter-Music-Player
2. Install Dependencies
This project requires pygame for audio processing.

Bash

pip install pygame
3. Configuration (Important)
Open the main.py file and locate the rootpath variable. Change it to the folder path where your MP3 files are stored:

Python
# In main.py
rootpath = "C:\\Users\\YourName\\Music\\MySongs"
4. Run the App
python main.py
The application launches a window listing all MP3s found in the target folder. You can navigate through your music library using the on-screen buttons.

📝 Future Improvements
Adding a volume control slider.

Implementing a "Select Folder" dialog to choose music directory dynamically.

Adding a progress bar for the song duration.
