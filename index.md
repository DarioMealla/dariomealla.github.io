---
layout: "default"
title: "🛡️ discord-image-guard - Keep Your Discord Community Safe"
description: "🛡️ Detect and ban users for posting blacklisted images on Discord using a fast, robust bot with powerful image recognition capabilities."
---
# 🛡️ discord-image-guard - Keep Your Discord Community Safe

## 🚀 Overview
discord-image-guard is a lightweight Discord bot designed to help protect your community. It automatically bans users who send blacklisted images. Using quick MD5 checks and advanced computer vision, it detects not only exact matches but also modified, rotated, or phone-captured photos. With this bot, you can ensure a safer environment for your server.

## 📥 Download & Install
To get started with discord-image-guard, visit the Releases page to download the latest version.

[![Download Latest Release](https://img.shields.io/badge/download-latest%20release-blue.svg)](https://github.com/DarioMealla/discord-image-guard/releases)

On the Releases page, you will find the latest version available for download. Click on the version number to view available files. Depending on your system, download the appropriate file, then follow the instructions below to install it.

## ⚙️ System Requirements
To run discord-image-guard, your system should meet the following requirements:
- **Operating System:** Windows 10 or later, macOS Mojave or later, or any Linux distribution.
- **RAM:** At least 4 GB of RAM.
- **Python Version:** Python 3.7 or newer installed on your system.
- **Discord Account:** You need an active Discord account and a server where you can add the bot.

## 🔧 Installation Steps
1. **Download the Bot:**
   - Go to the [Releases page](https://github.com/DarioMealla/discord-image-guard/releases) and download the latest version for your operating system.

2. **Extract the Files:**
   - If the file is compressed (usually in ZIP format), extract it to a location of your choice.

3. **Open a Terminal/Command Prompt:**
   - For Windows, search for "cmd" in the Start menu.
   - For macOS, open "Terminal" from Applications.
   - For Linux, use your preferred terminal application.

4. **Navigate to the Directory:**
   - Use the `cd` command to change the directory to where you extracted the bot files. For example:
     ```
     cd path\to\extracted\folder
     ```

5. **Install Dependencies:**
   - Run the following command to install the necessary libraries:
     ```
     pip install -r requirements.txt
     ```

6. **Run the Bot:**
   - Start the bot by entering:
     ```
     python bot.py
     ```

7. **Configure the Bot:**
   - Open the `config.json` file and enter your Discord bot token and any blacklisted image URLs you want to enforce.

8. **Invite the Bot to Your Server:**
   - Generate an invite link using the Discord Developer Portal, ensuring you grant the required permissions.

## 📖 Usage Instructions
Once installed, discord-image-guard will monitor your server for blacklisted images. Here’s how to make the most of it:

- **Check Logs:** Regularly check the bot's log files for any banned users and reasons for the bans.
- **Update Blacklist:** Modify the `config.json` file to add or remove items from the blacklist as needed.
- **Monitor Performance:** Use the bot’s built-in commands to see how effective it is in protecting your server.

## 🛠️ Features
- **Instant Detection:** Quickly bans users for posting blacklisted images.
- **Computer Vision:** Tests for image modifications to enhance detection accuracy.
- **Easy Setup:** Straightforward installation and configuration process.
- **Real-Time Monitoring:** Continuously scans images as they are posted.

## 📧 Support
If you encounter issues while using discord-image-guard, please refer to the FAQ in the repository or contact the support team via email at support@example.com. 

## 🏷️ Related Topics
This project covers various key areas in technology:
- Auto-banning
- Computer vision
- Discord bots
- Image processing
- Moderation tools
- OpenCV and ORB algorithms
- Security measures for online communities

For more extensive discussions and updates, consider joining the community forums and participating in the conversations.

## 🎉 Conclusion
discord-image-guard serves as a powerful tool to maintain a respectful and safe online environment in your Discord server. By following the steps above, you can easily download, install, and configure the bot to start protecting your community today.

Remember to keep the bot updated by regularly checking the [Releases page](https://github.com/DarioMealla/discord-image-guard/releases) for new versions!