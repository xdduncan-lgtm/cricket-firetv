PUBLISHING DARTS SCOREBOARD ON THE AMAZON APPSTORE
==================================================

PART 1 - Add your signing key to GitHub (once, about 5 minutes)
Your private signing key is in the separate "PRIVATE-signing-key" download.
Do NOT upload those files to GitHub; they go into GitHub "secrets" instead.
1. Open github.com/xdduncan-lgtm/cricket-firetv > Settings >
   Secrets and variables > Actions > New repository secret.
2. Name: KEYSTORE_BASE64   Secret: paste everything in KEYSTORE_BASE64.txt. Add secret.
3. New repository secret again.
   Name: KEYSTORE_PASSWORD   Secret: paste what's in KEYSTORE_PASSWORD.txt. Add secret.
4. Save the PRIVATE-signing-key files somewhere safe (e.g. a USB drive or password
   manager). You need the same key for every future update in the store.

PART 2 - Upload the new version (Windows computer)
1. Unzip this download.
2. In your GitHub project click Add file > Upload files. From this cricket-firetv
   folder drag in the "app" folder, the ".github" folder and PRIVACY.md.
   Click Commit changes. (Existing files are replaced.)
3. Watch Actions for the green check mark. Your download link is unchanged:
   https://github.com/xdduncan-lgtm/cricket-firetv/releases/latest/download/cricket.apk

PART 3 - Your own Fire Stick
The app is now "Darts Scoreboard" with a new app ID, so uninstall the old
"Cricket Scoreboard" once, then install with Downloader from the same link.
From now on, updates install over the top without uninstalling.

PART 4 - Submit to Amazon
1. Go to developer.amazon.com, sign in with your Amazon account, finish the free
   developer registration.
2. Dashboard > Amazon Appstore > Add a New App > Android. Title: Darts Scoreboard.
3. Upload Your App File: download cricket.apk from the link in Part 2 and upload it.
   (Rename it darts-scoreboard.apk first if you like.)
4. Target Your App: choose Fire TV devices (the Fire OS sticks). Phones and
   tablets can be unticked.
5. Appstore Details: paste the text from STORE-LISTING.txt and upload the images
   from the store-assets download.
6. Content rating: answer "None" throughout. Price: Free. Availability: your choice
   of countries.
7. Submit. Amazon tests the app on real Fire TV devices before it goes live and
   emails you the result.

When you change the app later: upload the changed file to GitHub, wait for the
build, then in the Developer Console add a new version and upload the new APK.
Version numbers go up automatically with each build.
