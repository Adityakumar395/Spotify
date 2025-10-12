**Spotify Clone Music Player** 

This is a basic, functional clone of a music player interface inspired by Spotify. It features a playlist of songs and simple play/pause functionality controlled by both a main play button and individual playlist rows.

**Features**

Playlist Display: Shows a list of songs with title, artist, and duration using a clear, table-based layout.

Central Play/Pause Control: A dedicated control button at the top of the playlist to play or pause the currently loaded song.

Row-Click Playback: Clicking any song row (<tr>) in the playlist will load and begin playing that specific track.

Thematic Design: Uses a banner image and clear headings to mimic a Spotify playlist view, specifically for a "Deep Focus" playlist.

**Technologies Used**

This project is built using fundamental web technologies:

**Technology	Purpose**

HTML5	Structures the content, including the playlist table and the <audio> element for playback.
CSS3	Handles the styling (referenced by style.css) to create the visual layout and resemblance to the Spotify interface.
JavaScript	Provides the interactive functionality for music playback, including the playaudio() and playAll(index) functions.

**Export to Sheets**

Setup and Installation 
To run this project locally, follow these steps:

Clone the Repository (if applicable) or download the files.

Ensure File Structure: Make sure you have the following essential files and folders in your project directory:

index.html (The provided HTML code)

style.css (The necessary CSS file)

script.js (The necessary JavaScript file)

**Images Folder:**

A folder named images containing:

play-button.svg (The image for the play control).

**Song Files:**

You will need to provide the actual song audio files and update the script.js file to load them correctly based on the playAll() logic.

**Open in Browser:**

Simply open the index.html file in your preferred web browser.

**Key Code Highlights**

1. Audio and Controls
   
The core playback is handled by a hidden <audio> element and a control button that triggers the main JavaScript function.

2. Playlist Interactivity

Each song row is set up to call a JavaScript function, passing its corresponding song number as an argument.
