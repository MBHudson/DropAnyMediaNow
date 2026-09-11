# Drop Any Media Now (D·A·M·N)

![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)

Stop uploading your private files to big tech clouds just to share them. **Drop Any Media Now** turns your Android device into a direct, private web server. Whether you're on the same Wi-Fi or sharing across the globe, your files stay on your hardware until the moment they are downloaded.

### Why use this?
Most file-sharing apps require you to trust their servers with your data. This app removes the middleman entirely. It uses professional-grade tunneling and encryption to ensure that "anonymous" actually means anonymous.

### Core Features
*   **Direct Hosting**: Serve files or entire folders directly from your local storage.
*   **Tor Integration**: Generate a `.onion` address to stay completely anonymous and bypass firewalls.
*   **Ngrok Tunnels**: Create a secure public URL for your local server with one tap.
*   **NAT Traversal**: Automatic UPnP configuration to handle router port forwarding for you.
*   **Privacy First**: No accounts, no tracking, and zero cloud storage.

### Tech Highlights
Built for modern Android (Target SDK 35) using Kotlin and Jetpack Compose. It leverages the Guardian Project's Tor implementation and native Ngrok binaries to provide stable, encrypted tunnels from a mobile environment.

### Development
```bash
./gradlew assembleDebug
```
Requires JDK 17 and Android Studio Ladybug or newer.

---

### License & Privacy
This project is licensed under the **GNU General Public License v3.0**. 
For the full privacy disclosure, see our [Privacy Policy](file:///C:/Users/BinBash/Documents/DAMN-UI/privacy-policy.md).
