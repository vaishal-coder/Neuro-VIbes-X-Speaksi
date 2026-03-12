<div align="center">
  <h1>Neuro VIbes X SpeakSi</h1>
  <p><strong>A seamless communication bridge for everyone.</strong></p>
  <p>
    <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
    <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  </p>
</div>

---

SpeakSi is a cross-platform mobile application built to make communication effortless and accessible. By providing real-time speech-to-text and text-to-speech capabilities, it serves as a reliable conversational layer for those who need it most, including users with speech or hearing impairments.

Whether you rely on it for everyday interactions, multi-language translation, or as a dependable offline assistant, SpeakSi is designed to just work, thoughtfully and securely.

---

## Key Features

- **Real-Time Speech-to-Text:** Converts spoken words into highly accurate text instantly, allowing for natural conversation flow.
- **Natural Text-to-Speech:** Generates lifelike voice output from text, making responses feel more human.
- **Multi-language Translation:** Translates both speech and text on the fly to help break down language barriers.
- **Accessibility Centered:** Built from the ground up to support users with hearing or speech challenges, fostering more inclusive daily interactions.
- **Dynamic Voice Customization:** Offers various voice styles and regional accents to personalize the user experience.
- **Offline Functionality:** Core speech and text processing continue to operate without an internet connection, ensuring you are never left without a way to communicate.
- **Intuitive Interface:** A clean, distraction-free design that prioritizes ease of use and quick navigation.

---

## Technology Stack

### Frontend
- **Flutter:** Used for building a robust, responsive application across iOS and Android.
- **Hive & SQLite:** Provide reliable local storage to power our offline capabilities.

### Backend & Infrastructure
- **Firebase Services:** Handles secure user authentication (Email and Google), real-time database needs via Cloud Firestore, and file storage.
- **Supabase:** Integrated as an open-source backend alternative.

### APIs & AI Integration
- **Google Cloud Speech-to-Text API:** Powers the core speech recognition.
- **Azure Text-to-Speech:** Delivers the natural-sounding voice generation.
- **Google Translate API:** Enables the rapid translation engine.
- **Custom Deep Learning Models:** A dedicated Python (Flask) backend tailored for specialized processing.

---

## Getting Started

If you'd like to run a local copy of SpeakSi or contribute to its development, follow these steps.

### Prerequisites

Ensure you have the following installed on your machine:
- Flutter SDK (Version 3.5.1 or newer)
- Android Studio or Xcode for running emulators
- A configured Firebase project linked to your local build

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/aisvamalar/SpeakSi.git
   ```

2. Navigate into the application directory:
   ```bash
   cd SpeakSi/SpeakSi1
   ```

3. Install the required Flutter dependencies:
   ```bash
   flutter pub get
   ```

4. Setting up the AI Deep Learning Models (Optional but recommended):
   You can find the backend neural-network endpoints and setup instructions in our [SpeakSi Flask APIs Workspace](https://github.com/ManojKira2112/speaksi_flask_apis).

5. Launch the application:
   ```bash
   flutter run
   ```

---

## Project Architecture

```text
SpeakSi/
└── SpeakSi1/                     # Main Flutter Application
    ├── android/                  # Android Native Configuration
    ├── ios/                      # iOS Native Configuration
    ├── lib/                      # Flutter Dart Code
    │   ├── main.dart             # Application Entry Point
    │   ├── screens/              # Core UI and Pages
    │   ├── widgets/              # Reusable Modular UI Components
    │   ├── services/             # Backend, FireBase, and API integrations
    │   └── utils/                # Utilities, Constants, and Helpers
    └── assets/                   # Images, Audio files, Fonts, and Icons
```

---

## Screenshots

*(We will be adding project screenshots here shortly to showcase the user interface.)*

<p align="center">
  <img src="https://via.placeholder.com/200x400?text=Home+Screen" width="200" alt="Home Screen Placeholder"/>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://via.placeholder.com/200x400?text=Translation" width="200" alt="Translation Screen Placeholder"/>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://via.placeholder.com/200x400?text=Settings" width="200" alt="Settings Screen Placeholder"/>
</p>

---

## The Team

SpeakSi was built by a small team dedicated to improving accessible communication.

| Name | Role | Contact |
| :--- | :--- | :--- |
| **Aisva Malar A** | Project Owner & Developer | [aishuarou656@gmail.com](mailto:aishuarou656@gmail.com) |
| **Vishwa P** | Core Developer & AI | [vishwa.fury@gmail.com](mailto:vishwa.fury@gmail.com) |

---

<div align="center">
  <i>Built to make communication accessible, natural, and reliable for everyone.</i>
</div>
