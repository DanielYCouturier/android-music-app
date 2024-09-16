# Android Music App
The purpose of this project was to create an app that would allow the user to organize and play mp3 files. The functionality was intended to be similar to popular alternatives such as Spotify, Pandora, or Apple Music, however these existing alternatives host several undesirable features regarding song licensing, offline capabilities, collection of user data, or subscription fees. My app was intended to be offline-only, and eliminate these undesirable features. I also have a personal stake in this project and wanted to create something I would be able to use daily.

The basic functionalities of the app include the ability to add create playlists, add songs to playlists from the filesystem or another playlist, edit or delete songs within each playlist, and edit or delete the playlists themselves. Finally, each playlist should have controls for playback, including play/pause, skip to next or previous track, shuffle playlist, and loop playlist.

# Basic Design
* MainActivity.kt - Main recycler view for displaying all user-created playlists.
* PlaylistViewFragment.kt - Secondary recycler view for displaying all songs within a selected playlist.
* SongQueue.kt - Main Data Structure to synchronize playback features which otherwise interfere with each other.
* SongData.kt, PlaylistData.kt - Data classes to hold objects in memory, also handles all read/write calls to Android file system. 
* __________Fragment.kt - These classes represent widgets that implement a specific feature, such as editing playlists, or adding a new song from file system.
* Misellaneous helper classes.

This project was originally submitted as a final project for COP 4655 (Application Development for Mobile Devices) (2024)
<img src="https://github.com/user-attachments/assets/2b847dd6-a4d1-4afe-a766-aaa81e6c344e" width = 200/>

![image](https://github.com/user-attachments/assets/ddf538b0-a39c-4f2d-88c4-7b586bd2571c)

Targeted for Android SDK 34, Min SDK 24+, JVM 1.8, Gradle 8.7, Android Studio Koala 2024

[Original Report](https://docs.google.com/document/d/1fsWPQsA1NCxGTaaQ5Hz-7cLcFM4IV1FLSiXeR1HyJqs/edit?usp=sharing)
