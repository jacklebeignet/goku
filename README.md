<p align="center">
  <img src="https://cdn.pfps.gg/pfps/5277-goku-ultra-instinct.gif" width="150" height="150">
  <h1 align="center">GOKU - Discord Raid Bot</h1>
</p>

<p align="center">
  <a href="https://github.com/jacklebeignet/goku/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/jacklebeignet/goku?style=social"></a>
  <a href="https://github.com/jacklebeignet/goku/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/jacklebeignet/goku?style=social"></a>
  <a href="https://github.com/jacklebeignet/goku/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/jacklebeignet/goku"></a>
  <a href="https://github.com/jacklebeignet/goku/commits/main"><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/jacklebeignet/goku"></a>
</p>

<p align="center">
GOKU is a <b>Discord raid bot</b> designed for <b>educational and development purposes only</b>. It allows users to send automated messages and flood a server with custom spam messages without admin permissions.  
</p>

---

## 📑 Table of Contents
- [How It Works](#-how-it-works)
- [Commands](#-commands)
- [Demonstration](#-demonstration)
- [Example Usage](#-example-usage)
- [Installation](#-installation)
- [Star History](#%EF%B8%8F-star-history)

---

## 📌 How It Works  
1. **Add the bot to your server**  
2. **Use slash commands** to execute actions  
3. **Watch it spam messages** in public channels  

---

## 📜 Commands  

### `/kill`  
🔹 Starts spamming a preset raid message.  

### `/kill-custom <message>`  
🔹 Spams the server with a **custom message**.  

### `/send <message> [anonymous]`  
🔹 Sends a **single message**, either publicly or anonymously.  

### `/help`  
🔹 Displays bot information and the support server link.  

## ⚙ Demonstration  

This bot is also self-hosted by me. You can invite it on our Discord server: **[dsc.gg/beignet](https://discord.gg/sc5tfyEUqD)**.  

## 🚀 Example Usage

> [!IMPORTANT]  
> For the commands to work, it is necessary to have the **'Use External Apps'** permission enabled in the current channel. Otherwise, the messages will be private and will only be seen by the user itself. You can use Vencord's Plugin called [PermissionsViewer](https://vencord.dev/plugins/PermissionsViewer) to see the permissions in the channel.

```sh
/kill
# The bot floods the channel with pre-made raid messages
```

```sh
/kill-custom text:Hello
# The bot floods the channel with custom raid messages
```

```sh
/send text:Hello anonymous=True
# The bot sends a simple message anonymously.

/send text:Hello anonymous=False
# The bot sends a simple message, but the username of the person is visible.
```

## 🔧 Installation  

1. [**Download the latest release**](https://github.com/jacklebeignet/goku/releases/latest).
   
3. **Unarchive the ZIP file you downloaded from the release.**

4. **Install the dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
5. **Add your bot token:**
   
   Open src/TOKEN.txt and paste your Discord bot token inside.

6. **Run the bot:**
   ```sh
   python bot.py
   ```
## ⭐️ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=jacklebeignet/goku&type=Date)](https://www.star-history.com/#jacklebeignet/goku&Date)
