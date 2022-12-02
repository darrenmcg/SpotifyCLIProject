Spotify Music Downloader

This is a python CLI Project that downloads a song from spotify alongside its meta data.
This works by cross-referencing the song on YouTube and downloading it through a library called Pytube then converts it to an mp3 with the use of Mutagen library. 
This project uses Spotipy library to interact with Spotify API

Prerequisites
Run command in the terminal after locating project directory:
```
pip install -r requirements.txt
```
This will install all needed modules and libraries required to run project

Getting Started
1) Create a Spotify Dev Account on https://developer.spotify.com/dashboard/
2) Create an App By Clicking on Create An App. Enter in app name and description.
3) Click On App and there you will see Client ID and Client Secret. Take a note of these
4) Open Your Terminal (Bash terminal) and run 'git clone https://github.com/darrenmcg/SpotifyCLIProject
5) run 'cd SpotifyCLIProject'
6) run 'export SPOTIPY_CLIENT_ID='INSERT CLIENT ID' '
7) run 'export SPOTIPY_CLIENT_SECRET='INSERT CLIENT SECRET' '
8) Now you are ready. Run  'python project.py' and follow the given instructions to download the song from spotify.