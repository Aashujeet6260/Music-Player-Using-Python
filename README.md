🎵 Music Player Application using Python (Tkinter & Pygame)
A desktop-based Music Player application built with Python, featuring a graphical user interface using Tkinter and audio playback functionality using Pygame. The player supports playing .mp3, .wav, and .ogg audio files from a local directory with basic controls: Play, Pause, Unpause, and Stop, along with a scrollable playlist UI.

🚀 Features
🎧 Play, pause, unpause, and stop music tracks

📂 Dynamic playlist loaded from a local directory

🖥️ Clean and responsive GUI built with Tkinter

🔄 Cross-platform compatibility (Windows, macOS, Linux)

🧠 Object-Oriented design for modular, maintainable code

📷 GUI Preview
![Screenshot 2025-06-22 052612](https://github.com/user-attachments/assets/2bc2a2bd-8daa-4046-b6fd-4574385f5e4c)


🛠️ Tech Stack
Python 3.x

Tkinter (Standard GUI Library)

Pygame (pygame.mixer for audio control)

OS (Standard Library for directory access)

🧠 OOP Concepts Used
MusicPlayer class encapsulates the entire application

__init__() constructor sets up UI and logic

Instance variables maintain current track and status

Core functionality like playsong(), pausesong() defined as class methods

Demonstrates encapsulation and modular design

📂 Project Structure
bash
Copy
Edit
music-player/
│
├── main.py               # Main application script
├── /songs                # Folder containing .mp3/.wav files
└── README.md             # Project documentation
⚙️ How to Run the Project
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/music-player.git
cd music-player
2. Install Dependencies
bash
Copy
Edit
pip install pygame
Tkinter comes pre-installed with Python. If not, install it using:

bash
Copy
Edit
sudo apt-get install python3-tk  # For Linux
3. Add Songs
Create a folder named songs in the project directory.

Add your .mp3, .wav, or .ogg files into the songs folder.

4. Update Path in Code
In main.py, update the directory path:

python
Copy
Edit
os.chdir("PATH_TO_YOUR_SONG_FOLDER")
Example:

python
Copy
Edit
os.chdir("./songs")
5. Run the App
bash
Copy
Edit
python main.py
📌 TODO (Optional Enhancements)
Add volume control

Implement Next/Previous track buttons

Display song duration and progress bar

Allow drag and drop song addition

📃 License
This project is open source and available under the MIT License.
