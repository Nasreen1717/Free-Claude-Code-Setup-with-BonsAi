# 🚀 Free Claude Code Setup with BonsAI

A comprehensive guide to using Claude Code for free through the Bonsai CLI — no API key or paid subscription required.

## 📖 Overview

Bonsai provides access to frontier AI models (including Claude) in stealth mode, where model names are hidden to ensure unbiased evaluation. This guide walks you through setting up and using Claude Code completely free.

## ✨ Features

- ✅ **100% Free** - No API key or subscription needed
- 🔒 **Stealth Mode** - Model names hidden for unbiased testing
- 🎯 **Easy Setup** - Just a few commands to get started
- 🌐 **Cross-Platform** - Works on Windows, Linux, and macOS

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (v18 or higher recommended)
- **npm** (comes bundled with Node.js)
- Any terminal/command prompt

### Check Your Versions

```bash
node -v
npm -v
```

## 🛠️ Installation & Setup

### Step 1: Install Bonsai CLI

Install the Bonsai CLI globally using npm:

```bash
npm install -g @bonsai-ai/cli
```

Verify the installation:

```bash
bonsai --version or npx bonsai --version
```

### Step 2: Authenticate with Bonsai

Log in to your Bonsai account:

```bash
bonsai login or npx bonsai login
```

**What happens during login:**
- A browser window opens automatically
- You log in or sign up for a Bonsai account
- Your terminal gets authenticated securely

### Step 3: Start Claude Code

Launch a Claude Code session:

```bash
npx bonsai start claude
```

**What this command does:**
- Launches a Claude Code session
- Automatically assigns a frontier model
- Runs in stealth mode (model name hidden)
- No API key required

### Step 4: Logout (Optional)

When you're done, you can logout:

```bash
bonsai logout or npx bonsai logout
```

## 🎯 Use Cases

This setup is perfect for:

- 👨‍🎓 **Students** - Learn AI development without costs
- 👩‍💻 **Developers** - Prototype and test AI applications
- 🎥 **Content Creators** - Create AI-powered content
- 🏆 **Hackathon Participants** - Build quickly without infrastructure costs

## 💡 Why BonsAI?

- **No Credit Card Required** - Start immediately
- **Frontier Models** - Access to state-of-the-art AI
- **Unbiased Testing** - Stealth mode ensures fair evaluation
- **Simple CLI** - Easy to use command-line interface

## 📚 Additional Resources

- [Bonsai Documentation](https://bonsai.ai/docs)
- [Claude Documentation](https://docs.claude.com)
- [Node.js Download](https://nodejs.org)

## ⚠️ Troubleshooting

### Installation Issues

If you encounter permission errors during installation, try:

```bash
sudo npm install -g @bonsai-ai/cli
```

### Login Problems

- Ensure your browser allows pop-ups
- Check your internet connection
- Clear browser cache if authentication fails

### Command Not Found

If `bonsai` command is not recognized:
- Restart your terminal
- Check npm global bin path: `npm config get prefix`
- Add npm global bin to your PATH

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🌟 Show Your Support

Give a ⭐️ if this project helped you!

---

**Happy Coding!** 🚀🤖

