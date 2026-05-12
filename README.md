# VoiceNotes

VoiceNotes is a modern SwiftUI voice recording application built using SwiftUI, SwiftData, AVFoundation, and Combine.

The app allows users to:

* Record audio notes
* Pause and resume recordings
* Play audio recordings
* View waveform animations
* Rename recordings
* Delete recordings
* Search recordings
* Filter recordings
* Persist recordings locally using SwiftData

---

# Features

## Audio Recording

* High-quality AAC audio recording
* Pause and resume support
* Real-time waveform animation
* Live recording timer
* Haptic feedback interactions

## Audio Playback

* Play / pause recordings
* Seek through audio
* Playback waveform visualization
* Forward and backward controls

## Recording Management

* Rename recordings
* Delete recordings
* Search recordings instantly
* Filter recordings:

  * All
  * Shared
  * Starred

## Modern UI

* Built entirely with SwiftUI
* Smooth animations
* Custom recording overlay
* Responsive bottom sheet player
* Clean minimal interface

---

# Tech Stack

* SwiftUI
* SwiftData
* AVFoundation
* Combine
* MVVM Architecture

---

# Project Structure

```
VoiceNotes/
├── Models/
├── Services/
├── ViewModels/
├── Views/
├── Components/
├── Utilities/
└── Resources/
```

---

# Architecture

The project follows the MVVM architecture pattern.

## Layers

### Views

Responsible for UI rendering and user interaction.

### ViewModels

Handle business logic and state management.

### Services

Responsible for audio recording and playback functionality.

---

# Permissions

The app requires microphone access.

Add the following key to `Info.plist`:

```xml
<key>NSMicrophoneUsageDescription</key>
<string>VoiceNotes needs microphone access to record audio.</string>
```

---

# Installation

## Requirements

* Xcode 16+
* iOS 18+
* Swift 6

## Steps

1. Clone the repository
https://github.com/MidlajMc/VoiceNotes.git

2. Open the project in Xcode

```bash
open VoiceNotes.xcodeproj
```

3. Run the app on Simulator or a real device

---

# Recording Flow

1. Tap the record button
2. Grant microphone permission
3. Start recording
4. Pause or resume anytime
5. Tap done to save recording
6. Tap a recording to play it

---

# Search & Filters

Users can:

* Search recordings by title
* Filter recordings using tabs
* View contextual empty states

---

# Future Improvements

* Cloud sync
* AI transcription
* Audio trimming
* Folder organization
* Sharing support
* Background recording
* iCloud backup

---

# Screenshots
<img width="1170" height="2532" alt="Simulator Screenshot - iPhone 13 - 2026-05-12 at 21 30 16" src="https://github.com/user-attachments/assets/91ea42f6-87a8-4bdf-88d5-ddd58f42ecf7" />
<img width="1170" height="2532" alt="Simulator Screenshot - iPhone 13 - 2026-05-12 at 21 30 22" src="https://github.com/user-attachments/assets/935ac59f-5329-487f-bd4e-c2ab88e07053" />


---

# License

MIT License

---

# Author

Created by Midlaj Mc
