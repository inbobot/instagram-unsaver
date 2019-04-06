# Instagram Unsaver
An open source Chrome Extension allowing you to clear all your saved Instagram posts at once.
![preview](https://s2.gifyu.com/images/InstagramUnsaver-PreviewTest.gif "Preview")

## Features
- Mass post unsaving
- Unsaving previously selected posts
- Unsaving all posts except previously selected ones **(soon)**

## How to install
#### As the extension is not yet available in the chrome web store, things are a little more complicated:
1. Go to [releases](https://github.com/thisismo/instagram-unsaver/releases) and download the latest .zip file
2. Unpack the downloaded zip files (manifest.json + assets folder) in to a new and empty folder
3. Open up **chrome://extensions/** and activate the Developer Mode in the top-right corner
4. Click **Load unpacked** and select the previously unpacked folder
5. Go to [Instagram](https://www.instagram.com/) and login if needed
6. Head to **Your Profile** -> **Saved** -> Click **Unsave All**  
   or alternatively go to `https://www.instagram.com/[your username]/saved/`
7. Let the script finish its work and hit **Done**

## To do:
- Unsave all **except** previously selected posts
- Prevent the script from exceeding Instagrams Max Request Limit (200 Requests / 5 Minutes)
