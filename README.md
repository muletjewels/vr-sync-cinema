# 🎬 VR Sync Cinema

A free, browser-based room that allows you to watch local files or online videos together in perfect synchronization.

Works on **Oculus Quest 1, ... Quest 3, Phones and other devices with browsers.**.

![Version](https://img.shields.io/badge/version-1.0-blue) ![License](https://img.shields.io/badge/license-MIT-green)

## 🌟 Why use this?

* **Zero Config:** No app installation, no server setup, and no accounts required.
* **Works Offline (via P2P):** Once connected, your headsets talk directly to each other.
* **File Sharing:** Host a video on your PC and stream it directly to your friends' VR headsets without uploading to the cloud.
* **Dual Control:** Both the Host and Guests can pause, play, and seek the video.

## ⚡ Features

* **Room Codes:** Create custom room names (e.g., `friday-night-movie`) or use random generated codes.
* **Live Availability Check:** Instantly checks if a room name is taken before you create it.
* **Local File Transfer:** Send video files from your PC hard drive to VR headsets wirelessly.
* **URL Streaming:** Paste any direct MP4/WebM link to watch.
* **Cross-Platform:** Watch together regardless of whether your friend is on a Quest, a Phone, or a Laptop.

## 🚀 How to Use

### 1. The Host (The Controller)

1.  Open the app in your browser.
2.  Click **"I am HOST"**.
3.  Enter a unique Room Name (e.g., `my-room-123`). The app will tell you if it is available.
4.  Click **Create Room**.
5.  **Share the Room Code** with your friends.
6.  **Select a Video:**
    * *Option A:* Click "Select Local File" to pick a video from your computer/phone.
    * *Option B:* Paste a direct video URL (MP4) into the box.
7.  Click **Load Video**. The video will load on your screen and wait for guests.

### 2. The Guests (The Viewers)

1.  Open the same app link on their device (Quest, Phone, etc.).
2.  Click **"I am GUEST"**.
3.  Enter the **Room Code** provided by the Host.
4.  Click **Connect**.
5.  The video will automatically load. When the Host presses play, everyone watches together.

## ⚠️ Important Limitations

### Quest 1 Users (RAM Warning)
Because this app transfers files directly through the browser (WebRTC), the file is loaded into the device's RAM (Memory) before playing.

* **Quest 1 (4GB RAM):** May crash if transferring files larger than **300MB-500MB**. For full movies on Quest 1, it is safer to use a direct URL link rather than local file transfer.
* **Quest 3 (8GB+ RAM):** Can handle larger file transfers (up to 1-2GB) easily.

### Video Formats
* **Supported:** MP4, WebM.
* **Not Supported (Usually):** MKV files are generally not supported by web browsers due to licensing. If you have an MKV file, convert it to MP4 first for the best experience.

## 🛠️ Technology

* **Frontend:** HTML5, CSS3, jQuery.
* **Networking:** PeerJS (WebRTC). The app uses the public PeerServer cloud only for the initial handshake (matchmaking); the video stream and commands are sent Peer-to-Peer.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---
Watch multiple devices online mp4 in sync, taken in consideration specifically Quest 1 and Quest 3 headsets
### Credits
Created for the VR community to enjoy movies together.
