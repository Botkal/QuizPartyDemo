# 🎉 QuizParty

A LAN-based multiplayer quiz game for Android — up to 10 players, no internet required.

> **Coming soon on Google Play**

---

## 📱 How It Works

QuizParty runs on a **TV or host device** (Android app). Players join from their phones — either through the **native Android client app** (auto-discovers the host via Wi-Fi) or through a **web browser** (no app needed).

```
Host (TV/Android)
    ├── Android client app  →  auto-connects via Wi-Fi discovery
    └── Web client          →  scan QR code or enter IP in browser
```

Each round, the question appears on the TV. Players answer on their phones. At the end, a combined scoreboard is shown.

---

## ✨ Features

- 📺 **TV / host app** — lobby, game flow, scoreboard
- 📱 **Native Android client** — auto-discovers host via Wi-Fi
- 🌐 **Web client** — join from any browser, no app needed
- ✏️ **Built-in web question editor** — manage, filter, and edit questions from a browser
- 🌍 **Multilingual question bank** — Hungarian, English, German (7,200+ questions, 15 categories)
- 🎯 **Difficulty levels** — Easy / Medium / Hard
- 🗂️ **Presets** — save game configurations with fixed question sections
- 📊 **Statistics** — track question usage and content quality

---

## 📸 Screenshots

### TV App — Lobby & Gameplay
| | | |
|---|---|---|
| ![](assets/Screenshot_QuizParty-2.png) | ![](assets/Screenshot_QuizParty-3.png) | ![](assets/Screenshot_QuizParty-4.png) |
| ![](assets/Screenshot_QuizParty-5.png) | ![](assets/Screenshot_QuizParty-6.png) | ![](assets/Screenshot_QuizParty-7.png) |
| ![](assets/Screenshot_QuizParty-8.png) | ![](assets/Screenshot_QuizParty-9.png) | |

### Web Client — Play from Browser
| | | |
|---|---|---|
| ![](assets/Web_game-client.png) | ![](assets/Web_game-client-2.png) | ![](assets/Web_game-client-3.png) |
| ![](assets/Web_game-client-5.png) | ![](assets/Web_game-client-6.png) | |

### Web Question Editor
| | |
|---|---|
| ![](assets/WebQuestionEditor.png) | ![](assets/WebQuestionEditor-1.png) |

---

## 🎬 Demo

| Gameplay | Web Client |
|---|---|
| [▶ Watch](assets/Running%20Devices%20-%20QuizParty%202026-05-11%2012-59-25.mp4) | [▶ Watch](assets/Running%20Devices%20-%20QuizParty%202026-05-11%2013-01-37.mp4) |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| TV / Host app | Kotlin, Jetpack Compose |
| Android client | Kotlin, Jetpack Compose |
| Web client | HTML / JavaScript |
| Question editor | HTML / JavaScript, Ktor server |
| Networking | LAN / Wi-Fi, QR code discovery |
| Database | Room DB |
| Question bank | JSON import / export |

---

## 🌍 Question Bank

7,200+ questions across 15 categories in 3 languages, generated and translated using an AI pipeline (Groq API + llama-3.1).

**Categories include:** Animals, History, Science, Geography, Sports, Music, Film, Technology, and more.

---

## 👤 Author

**László Botka**
[linkedin.com/in/lbotka](https://www.linkedin.com/in/lbotka) · [botkal.github.io/Page](https://botkal.github.io/Page/)
