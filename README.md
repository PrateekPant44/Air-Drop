# Airdrop – File Sharing Android App

Airdrop is a peer-to-peer file sharing mobile application developed using **Java** and **Android Studio**. It allows users to share files directly between Android devices without internet connectivity using **Wi-Fi Direct** or **Bluetooth**. The app is lightweight, secure, fast, and ideal for use in areas with limited or no internet access.

## 📌 Features

- 🚀 **Offline Peer-to-Peer File Sharing** – No need for the internet.
- ⚡ **High-Speed Transfers** – Transfers 100MB files in under 10 seconds.
- 📁 **Multi-Format Support** – Share images, audio, video, documents, and compressed files.
- 📱 **User-Friendly UI** – Designed using Material Design for ease of use.
- 🔒 **Secure Transfers** – Permission management and optional encryption for safety.
- 📊 **Progress Indicators** – Real-time file transfer status and history.
- 🔋 **Efficient & Lightweight** – Low battery and CPU usage, smooth performance.

## 🧱 Technology Stack

| Component              | Technology                     |
|------------------------|---------------------------------|
| Language               | Java                            |
| IDE                    | Android Studio                  |
| Communication Protocol | Wi-Fi Direct, Bluetooth         |
| UI Design              | XML, Jetpack, Material Design   |
| Database               | SQLite, SharedPreferences       |
| File Handling          | Java I/O, Sockets               |
| Security               | Android Permissions, JCA APIs   |

## 📲 Screenshots

*Screenshots are available in the `Screenshots` section of the project report.*

## 🛠 How It Works

1. **Device Discovery**: Uses Wi-Fi Direct to scan and list nearby devices.
2. **Connection Establishment**: Establishes peer-to-peer connection without the internet.
3. **File Selection**: User selects single or multiple files from device storage.
4. **File Transfer**: Data is transmitted via sockets using encrypted streams.
5. **Reception**: Receiver accepts files, stored in a pre-defined folder.

## 🔐 Security

- Android runtime permission model for secure access to storage and network.
- Optional encryption using JCA for secure file transmission.
- Files only accepted from authorized devices.

## 💡 Use Cases

- Remote education institutes
- Corporate environments with restricted networks
- Disaster-prone or low-network areas
- Events, conferences, or schools

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/PrateekPant44/Airdrop-Mobile-App.git
