<div align="center">
  <img src="https://raw.githubusercontent.com/walkxcode/dashboard-icons/main/png/youtube.png" width="128" height="128" alt="YouTube Icon"/>
  <h1>YouTube Clone for Android</h1>
  <p>A beautifully designed, feature-rich, and open-source YouTube client for Android built with modern Jetpack Compose.</p>

  <div>
    <img src="https://img.shields.io/badge/Platform-Android-3DDC84.svg?style=for-the-badge&logo=android" alt="Platform" />
    <img src="https://img.shields.io/badge/Kotlin-1.9.0-7F52FF.svg?style=for-the-badge&logo=kotlin" alt="Kotlin" />
    <img src="https://img.shields.io/badge/Jetpack%20Compose-UI-4285F4.svg?style=for-the-badge&logo=android" alt="Jetpack Compose" />
  </div>
</div>

---

## 🌟 Features

- **Ad-Free Experience:** Watch videos without any interruptions.
- **Background Playback:** Listen to videos even when the app is in the background or the screen is turned off.
- **Video & Audio Downloading:** Save videos directly to your device. Choose between audio-only or various video resolutions (1080p, 720p, 360p).
- **Picture-in-Picture (PiP):** Multitask seamlessly while a floating video player stays on your screen.
- **Modern UI:** A stunning, liquid-smooth user interface built entirely in Jetpack Compose, mimicking the real YouTube experience.
- **Library & History:** Keep track of your watch history, liked videos, and saved playlists locally.
- **Media3 ExoPlayer Integration:** High-performance, low-latency video streaming and buffering.

## 🛠 Tech Stack

This project is built using the latest and greatest in the Android development ecosystem:

- **Language:** [Kotlin](https://kotlinlang.org/)
- **UI Toolkit:** [Jetpack Compose](https://developer.android.com/jetpack/compose) (Material 3)
- **Media Player:** [AndroidX Media3 ExoPlayer](https://developer.android.com/media/media3)
- **Backend Extractor:** [NewPipeExtractor](https://github.com/TeamNewPipe/NewPipeExtractor) for parsing YouTube's backend structure without needing an API key.
- **Database:** [Room Database](https://developer.android.com/training/data-storage/room) for offline local storage (history, liked videos, downloads).
- **Image Loading:** [Coil](https://coil-kt.github.io/coil/compose/) for fast and asynchronous image decoding.
- **Concurrency:** Kotlin Coroutines and Flows for robust async execution.

## 🚀 Installation & Build Instructions

If you want to compile and build the app yourself, follow these commands. 

### Prerequisites
- **Git** installed on your machine.
- **Java Development Kit (JDK) 17** or higher.
- **Android Studio** (Koala or later recommended).

### 1. Clone the Repository

Clone the project to your local machine using git:

```bash
git clone https://github.com/d0x-dev/Youtube.git
cd Youtube
```

### 2. Build via Command Line (Gradle)

If you prefer using the command line without opening Android Studio, you can assemble the APK directly:

**For Windows (PowerShell/CMD):**
```cmd
.\gradlew clean
.\gradlew assembleDebug
```

**For macOS/Linux:**
```bash
./gradlew clean
./gradlew assembleDebug
```

Once the build successfully completes, you will find the generated APK in the following directory:
`app/build/outputs/apk/debug/app-debug.apk`

Install the APK directly to your connected device:
```bash
adb install app/build/outputs/apk/debug/app-debug.apk
```

### 3. Build via Android Studio

1. Open **Android Studio**.
2. Go to `File` > `Open` and navigate to the folder where you cloned the repository.
3. Wait for Gradle to finish syncing the project.
4. Select your connected Android device or an Emulator.
5. Click the green **Run (▶)** button or press `Shift + F10` to compile and launch the app.

## 📸 Screenshots

*(Add screenshots of your application here by placing them in an `/assets` folder and linking them)*

|<img src="https://via.placeholder.com/250x500.png?text=Home+Screen" width="250">|<img src="https://via.placeholder.com/250x500.png?text=Video+Player" width="250">|<img src="https://via.placeholder.com/250x500.png?text=Library" width="250">|
|:---:|:---:|:---:|
| **Home Screen** | **Video Player** | **Downloads & Library** |

## 🤝 Contributing

Contributions are always welcome! Feel free to fork the repository, make some improvements or bug fixes, and submit a Pull Request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## ⚖️ License

Distributed under the MIT License. See `LICENSE` for more information.
