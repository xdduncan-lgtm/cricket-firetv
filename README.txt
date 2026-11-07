CRICKET SCOREBOARD FOR FIRE TV
==============================
You need: your Windows computer (for the one-time GitHub step) and your Fire Stick.
Nothing to install on the computer. The app works on the Fire Stick with no internet.

PART 1 - Build the app (Windows computer, about 10 minutes, one time)
1. Unzip this download. You'll have a folder named "cricket-firetv".
2. Sign in at github.com. Click "+" (top right) > New repository.
   Name: cricket-firetv. Choose Public. Click Create repository.
3. On the new page click "uploading an existing file".
4. Open the cricket-firetv folder, select EVERYTHING inside it (including the
   ".github" folder), and drag it all onto the GitHub page. Click Commit changes.
5. Click the "Actions" tab. A build named "Build Fire TV app" starts by itself.
   Wait for the green check mark (3-5 minutes).
   - If nothing appears in Actions, the .github folder didn't upload. Click
     Add file > Create new file, type the name  .github/workflows/build.yml
     paste in the contents of that file from this folder, and Commit.
6. Your app's download link is now:
   https://github.com/YOUR-USERNAME/cricket-firetv/releases/latest/download/cricket.apk

PART 2 - Install on the Fire Stick (about 5 minutes, one time)
1. Turn on developer options: Settings > My Fire TV > About. Highlight your
   device name and press OK 7 times until it says you're a developer.
2. On the Fire Stick home screen, search for "Downloader" (orange icon by
   AFTVnews) and install it. It's free.
3. Settings > My Fire TV > Developer options > Install unknown apps >
   turn Downloader ON.
4. Open Downloader, type the download link from Part 1 step 6, press Go,
   then press Install. Choose Delete afterwards to free space (not the app).
5. "Cricket Scoreboard" is now in Your Apps & Channels (the square grid
   button on the home screen). Hold OK on it and choose Move to front.

USING THE REMOTE
  Up / Down ............ pick a number (20 to Bull), or Miss / Undo / Next / Menu
  Left / Right ......... Single, Double, Triple
  OK (center) .......... score the dart
  Rewind ⏪ ............ undo
  Fast-forward ⏩ ...... next player
  Play/Pause ⏯ ......... miss
  Back or Menu ☰ ....... menu (restart, change players)
  On the start screen, Back exits the app.

Notes
- The game in progress is saved on the Fire Stick if you exit.
- To update the app later: upload the changed file to GitHub, wait for the new
  build, uninstall the old app on the Fire Stick, then install with the same link.
- Flag images: Twemoji by Twitter/X and contributors, CC-BY 4.0.
