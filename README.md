# TalkBack App 🎙️

**TalkBack** is a simple React Native app built with Expo that uses the `expo-speech` API to convert user-typed text into spoken audio.

This app was created as an extra credit assignment for Bellevue College's DEV 272 (Spring 2025) to explore an Expo API not covered in class.

---

## 🚀 Features

- Type any text into the input field
- Tap “Speak” to hear the device read the text aloud

---

## 📱 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/jabuan0910/talkback-expo-speech.git
   cd talkback-expo-speech
---

## 🛠 Tech Stack

- [Expo](https://expo.dev/)
- [`expo-speech`](https://docs.expo.dev/versions/latest/sdk/speech/)
- React Native
- TypeScript (via Expo Router)

---

## ✍️ Reflection

For this extra credit assignment, I chose to explore the `expo-speech` library because it was a fun and accessible way to work with an API that wasn’t covered in class. I wanted to build something interactive that responded directly to user input in a unique way. The ability to type anything and have the app speak it aloud reminded me of how technology can assist with accessibility and enhance communication.

One of the challenges I encountered was figuring out where to place the code within an Expo Router–based project, since this structure was different from previous assignments. I also had to make sure I handled edge cases like empty input gracefully so the app wouldn’t try to speak nothing.

With more time, I would extend this app to let users change the voice, language, or pitch of the speech. It might also be interesting to implement a feature that reads out a list of saved phrases, similar to how assistive communication devices work. Overall, this project gave me a deeper understanding of how to integrate native device features using Expo libraries. It also showed me how quickly meaningful functionality can be added with just a few lines of code.
