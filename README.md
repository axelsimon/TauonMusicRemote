
# Tauon Music Remote

An attempt at making an Andorid remote controller app for the Tauon Music Box desktop app.

Development stage is in alpha and not ready for general use.

## Current target features / design brief

 - Multiple view are presented, **playlists**, **albums**, **tracks** and **now playing**.
 These show content from the users desktop Tauon library.
 - There are two modes of opperation, **remote control**, and **local playback**. 
 Local playback plays audio through the app.
 
## Possible future goals

 - Sync audio for offline playback?
 - Play users local music files?

## Issues / Work needed

 - [Major architectural issue] The app was initally designed around a model in which data
 structures could be shared amoung views. This turns out not to be suitalbe for Android. Views need to be
 made "lifecycle" compatible. (You can see the issue specifically when you rotate your device screen,
 the app will crash)
 - Consideration for tablet display sizes?
 - [Tauon API] Security? Authentication?
 
 ### How to test
 
  - The remote API is not in Tauon master yet. You will need to setup Tauon Music Box from git and checkout the `remote` branch.
  (Once you have Tauon Music Box from the "remote" branch running, no further setup is currently needed)


