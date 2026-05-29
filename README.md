# CurseOfStriga
Witcher Hack and Slash Game: The Curse Of Striga

# Striga — Unreal Engine 5 Dark Fantasy Prototype

> A dark fantasy action prototype inspired by Slavic folklore and *The Witcher*, developed in Unreal Engine 5.5.4.
> The project focuses on cinematic combat, atmospheric storytelling, enemy AI, and immersive environment design.

---

## 📖 Overview

**Striga** is a third-person dark fantasy prototype where the player takes the role of a Witcher sent to an abandoned castle to lift the curse of a Striga — the cursed daughter of a king.

The project was developed as part of a university game development project and demonstrates gameplay programming, AI systems, combat mechanics, cinematic presentation, UI systems, and environmental storytelling using Unreal Engine 5.5.4.

---

## 🎮 Core Features

* Third-person melee combat system
* Enemy AI with combat behaviours
* Health and damage systems
* Hit reactions and cinematic hit-stop feedback
* Dialogue and cinematic cutscenes
* Intro and outro sequences
* Atmospheric medieval fantasy environment
* Dynamic combat and ambient audio
* UI elements including enemy/player health bars
* Animation Blueprint combat system
* Environmental lighting and visual effects

---

## 🛠️ Technologies Used

* **Engine:** Unreal Engine 5.5.4
* **Programming:** Blueprint System
* **Audio:** Unreal Audio System
* **Animation:** Animation Blueprints / Montages
* **Version Control:** Git + GitHub
* **Target Platform:** Windows PC

---

## 📂 Project Structure

```text
Striga/
│
├── Content/
│   ├── Blueprints/
│   ├── Characters/
│   ├── Environments/
│   ├── UI/
│   ├── Audio/
│   ├── Animations/
│   ├── Effects/
│   └── Cinematics/
│
├── Config/
├── Saved/
├── Builds/
└── README.md
```

---

## ⚔️ Gameplay Summary

The player receives a contract from the King to investigate an abandoned castle haunted by a Striga.
While initially appearing to be a monster-hunting mission, the Witcher discovers that the creature is actually the King’s cursed daughter.

The objective is not only to survive the night, but potentially break the curse.

---

## 📸 Screenshots

> Add gameplay screenshots here before uploading to GitHub.

Recommended screenshots:

* Combat gameplay
* Castle environment
* Striga enemy
* Dialogue cutscene
* UI/health bars
* Atmospheric lighting

Example:

```md
![Combat Screenshot](Screenshots/combat.png)
```

---

## 🚀 Installation / Running the Build

### Requirements

* Windows 10 / 11
* DirectX 12 compatible GPU
* Keyboard & Mouse

### Running the Game

1. Download the latest release build
2. Extract the `.zip` archive
3. Run:

```text
Striga.exe
```

No additional installation required.

---

## 🎮 Controls

| Action       | Key               |
| ------------ | ----------------- |
| Move         | WASD              |
| Look         | Mouse             |
| Attack       | Left Mouse Button |
| Dodge / Roll | Space             |
| Interact     | E                 |
| Pause        | ESC               |

---

## 🧪 Testing

The project was tested for:

* Combat responsiveness
* Enemy AI behaviour
* Collision detection
* Animation synchronization
* UI functionality
* Gameplay flow
* Audio playback
* Cutscene triggering

### Known Issues

* Some Blueprint systems became large and difficult to maintain during development
* Minor animation timing inconsistencies may occasionally occur
* Certain combat edge cases can produce collision inaccuracies

---

## 🔧 Development Challenges

One of the biggest technical challenges involved Blueprint scalability and maintainability.
As systems expanded, some Blueprints became extremely large and difficult to debug.

The project highlighted the importance of:

* Modular architecture
* Event-driven gameplay systems
* Cleaner Blueprint organisation
* Better separation of gameplay logic

---

## 📈 Future Improvements

Planned improvements include:

* More advanced enemy AI
* Additional enemy types
* Expanded narrative sequences
* Improved animation blending
* Better combat feedback systems
* Refactoring large Blueprint systems into modular components
* Increased use of C++

---

## 📌 Version Information

| Version                    | Status                   |
| -------------------------- | ------------------------ |
| v0.1 Prototype             | Initial combat prototype |
| v0.2 Gameplay Update       | AI + combat improvements |
| v0.3 Presentation Build    | Cinematics + polish      |
| v1.0 University Submission | Final academic prototype |

---

## 👨‍💻 Developer

Developed by **Krzysztof Panek**
Games Programming Student

GitHub: *(Add your GitHub profile link here)*

---

## 📜 License

This project was created for educational and portfolio purposes.

Some assets may belong to their respective owners and are used strictly for academic demonstration.

---

## ⭐ Portfolio Notes

This project demonstrates:

* Unreal Engine 5 workflow
* Gameplay systems design
* Combat implementation
* AI behaviour systems
* Animation Blueprint logic
* UI integration
* Environmental storytelling
* Iterative game development process

---

## 📥 Release Build

The release build can be found in the **Releases** section of this repository.

Recommended release naming:

```text
Striga_v1.0_Win64.zip
```

Recommended GitHub tags:

```text
v0.1
v0.2
v0.3
v1.0
```

---

## ✅ Professional GitHub Checklist

Before publishing:

* [ ] Add gameplay screenshots
* [ ] Upload playable build
* [ ] Remove unnecessary files (`Saved`, `Intermediate`)
* [ ] Include `.gitignore`
* [ ] Verify executable works on another PC
* [ ] Ensure folder naming consistency
* [ ] Add version tags/releases
* [ ] Include testing evidence
* [ ] Proofread README
* [ ] Add short gameplay video/GIF
