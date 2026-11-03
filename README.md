
# 🎮 Game Hub

**Your personal game library and launcher for Windows.**

Game Hub is a Windows desktop application built with C# and WPF. It lets you organize your PC games in one place and launch them without having to search through folders every time.

## ✨ Features

- **Discord Login** — Sign in with your Discord account.
- **Personal Game Library** — Keep your games organized in one place.
- **Add Games** — Add games by selecting their executable files.
- **Launch Games** — Start your games directly from Game Hub.
- **Edit Games** — Update the details of games in your library.
- **Remove Games** — Remove games from your collection.
- **Account-Specific Libraries** — Keep game libraries separate for different Discord accounts.
- **Dark Theme** — A dark interface with a red accent design.

## 🖥️ Requirements

- Windows 10 or Windows 11
- 64-bit Windows
- Internet connection for Discord authentication

The published version is intended to be self-contained, so users should not need to install .NET separately.

## 📥 Download

Visit the [Releases page](https://github.com/YOUR-USERNAME/Game-Hub/releases) to download the latest version.

### Installation

1. Download the latest `Game-Hub-v1.0.0-Windows-x64.zip` file from Releases.
2. Extract the ZIP file to a folder.
3. Open the extracted folder.
4. Run `GameLauncher.exe`.
5. Sign in with Discord.
6. Add your games and start playing!

> **Note:** Windows may display a security warning for a newly released application that is not widely recognized.

## 🔐 Discord Authentication

Game Hub uses Discord authentication to identify the signed-in user.

Each Discord account has its own local game library, helping keep different users' collections separate.

## 💾 Data Storage

Game Hub stores game-library data locally on the user's computer.

The application uses the Windows local application data directory:

```text
%LOCALAPPDATA%\GameLauncher\GameLibraries\
```

Game data is stored separately for each Discord account.

## 🛠️ Built With

- C#
- .NET
- WPF (Windows Presentation Foundation)
- Visual Studio
- Discord OAuth2

## 🚧 Planned Features

- Workspace management
- Create, edit, and remove workspaces
- Organize games into separate workspaces
- Improved game-library customization
- More launcher settings

## 📌 Project Status

Game Hub is currently under development.

Features and the user interface may change as development continues.

## 🤝 Contributing

Suggestions, bug reports, and ideas are welcome!

If you find a bug or have an idea for a feature, feel free to open an issue in the repository.

## 📄 License

No license has been added yet.

Until a license is added, the source code is not automatically granted permission for reuse, modification, or redistribution.
