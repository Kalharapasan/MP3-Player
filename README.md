# 🎧 JobME MP3 Player

**JobME MP3 Player** is a desktop-based audio player built in **Java Swing** using the **JLayer MP3 library**.  
It provides a clean and responsive UI to play, pause, stop, and control the volume of MP3 files.  
<img width="703" height="249" alt="Capture" src="https://github.com/user-attachments/assets/6d4731ae-6eb5-4e61-98fc-b9d9c8f252fd" />

---

## ✨ Features

- 🎶 **Play, Pause, Stop** audio files (MP3 format)  
- 🔁 **Repeat mode** for continuous playback  
- 🔊 **Volume control and mute/unmute support**  
- 📂 **File chooser** to select local MP3 files  
- 🖼️ **Custom UI icons** for controls (play, pause, stop, etc.)  
- 🪄 Lightweight and easy-to-use Java Swing interface  

---

## 🧰 Technologies Used

- **Language:** Java  
- **Framework:** Swing (NetBeans Form Builder)  
- **Libraries:**  
  - [`jl1.0.1.jar`](http://www.javazoom.net/javalayer/javalayer.html) — JLayer MP3 decoding  
  - `jaco-mp3-player-0.9.3.jar` — additional MP3 support  
- **Build Tool:** Apache Ant (NetBeans auto-generated `build.xml`)  
- **IDE:** NetBeans 8.x or later  

---

## 🗂️ Project Structure

```
JobMEMP3Player/
├── build.xml                          # Ant build configuration
├── manifest.mf                        # Manifest for JAR packaging
├── jl1.0.1.jar                        # JLayer MP3 library
├── nbproject/                         # NetBeans project configuration
├── build/classes/jobme/pk/            # Compiled class files
│   ├── PlayerFrame.class              # Main player class
│   ├── FileTypeFilter.class           # File chooser filter
│   └── images/                        # Button icons (play, pause, volume, etc.)
├── dist/
│   ├── JobMEMP3Player.jar             # Executable JAR
│   └── lib/                           # Libraries for runtime
│       ├── jl1.0.1.jar
│       └── jaco-mp3-player-0.9.3.jar
└── src/jobme/pk/                      # (if source included)
    ├── PlayerFrame.java
    ├── FileTypeFilter.java
    └── images/
```

---

## ▶️ How to Run

### Option 1: Using the prebuilt JAR  
1. Navigate to the `dist/` folder.  
2. Double-click **`JobMEMP3Player.jar`**, or run from terminal:  
   ```bash
   java -jar JobMEMP3Player.jar
   ```

### Option 2: Running from NetBeans  
1. Open the project folder in **NetBeans**.  
2. Right-click the project → **Clean and Build**.  
3. Press **Run (F6)** to launch the player.  

---

## 🧩 Main Components

| File | Description |
|------|--------------|
| `PlayerFrame.java` | Main GUI class handling buttons, audio, and events |
| `FileTypeFilter.java` | Filters file chooser to accept only `.mp3` files |
| `jl1.0.1.jar` | MP3 decoding library |
| `images/` | Contains all control icons (play, stop, mute, etc.) |

---

## 🎨 UI Overview

The player window includes:  
- Toolbar with **Play / Pause / Stop / Volume** controls  
- File selection option (`Open`)  
- Status display for playback  
- Support for repeat and mute functionality  

---

## 💡 Developer Notes

- Ensure Java **JRE 8 or higher** is installed.  
- If icons do not display, confirm the `images/` folder is included in the JAR or classpath.  
- Modify `PlayerFrame.java` to change the default theme or button icons.  

---

## 📄 License

📄 [License](./LICENSE.md): Proprietary – Permission Required

---

