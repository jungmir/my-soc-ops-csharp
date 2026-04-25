🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

<div align="center">

# 🎲 Soc Ops

### The Ultimate Social Bingo Game for Breaking the Ice

Turn networking events into unforgettable moments. Meet new people, mark squares, and win with five in a row!

[🎮 **Play Now**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/) • [📚 **Explore the Lab**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/) • [⭐ **Learn More**](#features)

</div>

---

## ✨ Features

🎯 **Quick Setup** — No registration required. Start playing instantly.

🤖 **Built with .NET + Blazor** — Modern WebAssembly game running entirely in your browser.

🎨 **Polished UI** — Beautiful, responsive design optimized for any device.

💾 **Persistent State** — Your game progress saves automatically to local storage.

🧠 **Smart Game Logic** — Real-time bingo detection with instant win alerts.

🌍 **Offline Ready** — Blazor WebAssembly means it runs without a server.

---

## 🚀 Quick Start

### Prerequisites
- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) or higher

### Run Locally
```bash
cd SocOps
dotnet run
```

The game launches at `http://localhost:5166`

### Or Use GitHub Codespaces (Cloud-Based)
1. Open your repo on GitHub
2. Click **Code** → **Codespaces** → **Create codespace on main**
3. Wait for the devcontainer setup to complete
4. Run:
   ```bash
   cd SocOps
   dotnet run
   ```

---

## 📚 Interactive Lab Guide

Learn to build this game from scratch using modern .NET development practices:

| Part | Topic | Duration |
|------|-------|----------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Overview & Setup Checklist | — |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Context Engineering with GitHub Copilot | 30 min |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Design-First Frontend Development | 45 min |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Custom AI Agent: Quiz Master | 30 min |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Multi-Agent Orchestration | 45 min |

> 💡 **Prefer offline?** Lab guides are also available in the [`workshop/`](workshop/) folder.

---

## 🏗️ Project Structure

```
SocOps/
├── Components/        # Reusable Blazor components
│   ├── BingoBoard.razor
│   ├── BingoSquare.razor
│   ├── GameScreen.razor
│   ├── StartScreen.razor
│   └── BingoModal.razor
├── Services/         # Game logic & state management
│   ├── BingoGameService.cs
│   └── BingoLogicService.cs
├── Models/           # Data models
├── Data/             # Question database
└── wwwroot/          # Static assets & styles
```

---

## 🛠️ Build & Test

```bash
# Build the project
cd SocOps
dotnet build

# Run tests
dotnet test

# Deploy automatically on push to main via GitHub Pages
```

---

## 💡 How It Works

1. **Start a Game** — Click "Start Game" to generate a random 5×5 bingo board
2. **Find Matches** — Walk around and find people matching the squares (e.g., "bikes to work", "speaks 2+ languages")
3. **Mark Squares** — Tap squares as you find matches
4. **Get 5 in a Row** — Win with a row, column, diagonal, or the free space in the center
5. **Reset & Play Again** — Start a fresh board instantly

The center square is always a **free space** (marked automatically). All other squares are randomly selected from a curated list of social prompts.

---

## 📖 Technology Stack

- **Frontend**: Blazor WebAssembly (C#, Razor components)
- **Runtime**: .NET 10
- **Styling**: Custom CSS utilities (no external dependencies)
- **Storage**: Browser LocalStorage API
- **Deployment**: GitHub Pages

---

## 🎓 Educational Focus

This project demonstrates:
- ✅ Modern Blazor component architecture
- ✅ State management patterns
- ✅ Responsive UI design
- ✅ Game logic implementation
- ✅ AI-assisted development with GitHub Copilot
- ✅ Multi-agent orchestration strategies

Perfect for learning or teaching .NET development in an engaging, practical way.

---

## 🤝 Contributing

We welcome contributions! Check out the [CONTRIBUTING.md](CONTRIBUTING.md) guide for details.

---

## 📄 License

Licensed under the [MIT License](LICENSE).

---

<div align="center">

**Have fun! 🎉**

[Play the Game](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/) | [View Source](https://github.com/jungmir/my-soc-ops-csharp) | [Report Issues](https://github.com/jungmir/my-soc-ops-csharp/issues)

</div>
