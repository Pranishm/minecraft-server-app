<div align="center">

  <img src="assets/images/logo.png" alt="VANAKAMSMPs Logo" width="150" />

  <h1>🎮 VANAKAMSMPs</h1>
  <p><b>The Ultimate Community Hub for the VANAKAMSMPs Minecraft Network</b></p>

  <p>
    <a href="https://flutter.dev"><img src="https://img.shields.io/badge/Flutter-3.x-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter"></a>
    <a href="https://github.com/Pranishm/minecraft-server-app/releases"><img src="https://img.shields.io/github/v/release/Pranishm/minecraft-server-app?style=for-the-badge&color=00b0ff" alt="Release"></a>
    <a href="https://github.com/Pranishm/minecraft-server-app/releases"><img src="https://img.shields.io/github/downloads/Pranishm/minecraft-server-app/total?style=for-the-badge&color=00e676" alt="Downloads"></a>
    <a href="https://github.com/Pranishm/minecraft-server-app/blob/main/LICENSE"><img src="https://img.shields.io/github/license/Pranishm/minecraft-server-app?style=for-the-badge&color=ff5252" alt="License"></a>
  </p>

  <p>
    <a href="#-about">About</a> •
    <a href="#-features">Features</a> •
    <a href="#-live-preview">Preview</a> •
    <a href="#-installation">Installation</a> •
    <a href="#-roadmap">Roadmap</a>
  </p>

</div>

---

## 🚀 Live Preview

<div align="center">
  <img src="preview.gif" width="850" alt="App Live Preview" style="border-radius: 12px; box-shadow: 0 4px 14px rgba(0,0,0,0.2);"/>
</div>

---

## 📖 About

**VANAKAMSMPs** is the official companion application for the VANAKAMSMPs Minecraft Network. Designed with the community at its core, this app provides players with a unified platform to manage their accounts, monitor server health, and engage with the network directly from their mobile devices.

> Built with **Flutter** and **Material 3**, delivering a seamless, high-performance experience with fluid animations and responsive design.

---

## ✨ Features

<table>
  <tr>
    <td><b>🔐 Authentication</b><br>Secure Google Sign-In & Profile Management</td>
    <td><b>📊 Server Analytics</b><br>Live Server Status & Real-time Player Count</td>
  </tr>
  <tr>
    <td><b>📰 Community Updates</b><br>Live News, Events & Exclusive Giveaways</td>
    <td><b>💬 Social Engagement</b><br>Integrated Community Chat & Push Notifications</td>
  </tr>
  <tr>
    <td><b>⚡ Modern Experience</b><br>Material 3 UI, Smooth Animations & Dark Mode</td>
    <td><b>🛠 Convenience</b><br>Interactive Widgets, QR Features & In-App Updates</td>
  </tr>
</table>

---

## 📱 Screenshots

<div align="center">
  <table>
    <tr>
      <td align="center"><b>Home</b></td>
      <td align="center"><b>Server</b></td>
      <td align="center"><b>Events</b></td>
    </tr>
    <tr>
      <td><img src="screenshots/home.png" width="250" alt="Home Screen"/></td>
      <td><img src="screenshots/server.png" width="250" alt="Server Screen"/></td>
      <td><img src="screenshots/events.png" width="250" alt="Events Screen"/></td>
    </tr>
    <tr>
      <td align="center"><b>Profile</b></td>
      <td align="center"><b>Chat</b></td>
      <td align="center"><b>Settings</b></td>
    </tr>
    <tr>
      <td><img src="screenshots/profile.png" width="250" alt="Profile Screen"/></td>
      <td><img src="screenshots/chat.png" width="250" alt="Chat Screen"/></td>
      <td><img src="screenshots/settings.png" width="250" alt="Settings Screen"/></td>
    </tr>
  </table>
</div>

---

## 🛠 Tech Stack & Architecture

Built following modern mobile development standards:

*   **Framework:** [Flutter](https://flutter.dev/) (Dart)
*   **State Management:** [Riverpod](https://riverpod.dev/)
*   **Backend / Auth:** [Firebase](https://firebase.google.com/) & Google Sign-In
*   **Networking:** [Dio](https://pub.dev/packages/dio)
*   **Background Tasks:** WorkManager

<details>
<summary><b>📂 View Project Structure (Click to expand)</b></summary>

```text
lib/
├── app.dart
├── main.dart
├── screens/
├── widgets/
├── services/
├── providers/
├── models/
├── utils/
└── theme/
