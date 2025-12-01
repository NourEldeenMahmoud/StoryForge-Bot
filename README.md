# 🤖 Onboarding Bot

<div align="center">

![.NET](https://img.shields.io/badge/.NET-8.0-512BD4?logo=dotnet&logoColor=white)
![Discord.NET](https://img.shields.io/badge/Discord.NET-3.18.0-5865F2?logo=discord&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

**Discord bot for automated user onboarding with AI-generated personalized stories**

</div>

---

## 📝 Description

A Discord bot that automates the onboarding process for new server members. It creates personalized AI-generated stories using OpenAI GPT-4, tracks invite usage, manages roles (Outsider → Associate), and provides a seamless onboarding experience through private threads.

## ✨ Features

- 🤖 Automated onboarding with private threads
- 📖 AI-generated personalized stories (OpenAI GPT-4)
- 👥 Automatic role management
- 🔗 Invite tracking and inviter identification
- 💾 Story storage and retrieval
- 🔄 Existing user detection

## 🚀 Quick Start

1. **Clone & Setup**
   ```bash
   git clone https://github.com/NourEldeenMahmoud/Onboarding-Bot.git
   cd Onboarding-Bot
   dotnet restore
   ```

2. **Configure Environment**
   Create `.env` file:
   ```env
   DISCORD_TOKEN=your_discord_bot_token
   OPENAI_KEY=your_openai_api_key
   DISCORD_STORY_CHANNEL_ID=your_story_channel_id
   DISCORD_CITY_GATES_CHANNEL_ID=your_city_gates_channel_id
   DISCORD_OUTSIDER_ROLE_ID=your_outsider_role_id
   DISCORD_ASSOCIATE_ROLE_ID=your_associate_role_id
   ```

3. **Run**
   ```bash
   dotnet run
   ```

## 🚢 Deployment (Render)

1. Connect GitHub repository to Render
2. Create Web Service with:
   - **Build Command**: `dotnet build -c Release -o out`
   - **Start Command**: `dotnet out/Onboardingbot.dll`
   - **Environment**: Docker
3. Add environment variables
4. Deploy!

## 💻 Usage

Users type `/join` in the City Gates channel to start onboarding.

## 🔐 Required Permissions

- Send Messages
- Create Private Threads
- Manage Roles
- Read Message History
- Mention Everyone
- Use Slash Commands

## 🛠️ Tech Stack

- .NET 8.0
- Discord.NET 3.18.0
- OpenAI API
- RestSharp
- Newtonsoft.Json

## 📄 License

MIT License - see [LICENSE](LICENSE) file

---

## 📋 GitHub Repository Info

### Description (for GitHub)
```
Discord bot for automated user onboarding with AI-generated personalized stories. Features automated role management, invite tracking, and OpenAI GPT-4 story generation.
```

### Topics / Hashtags
```
discord-bot
discord
onboarding
openai
gpt-4
ai
csharp
dotnet
discord-net
automation
role-management
invite-tracking
story-generation
bot
discord-server
```

---

<div align="center">

**⭐ Star this repo if you find it helpful!**

Made with ❤️ by [Nour Eldeen Mahmoud](https://github.com/NourEldeenMahmoud)

</div>
