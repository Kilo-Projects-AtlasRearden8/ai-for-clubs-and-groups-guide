# Running Local AI for Clubs

A beginner guide to running AI models on your own computer, so nothing leaves
your machine. Ideal for privacy-sensitive club work like rosters and member
lists.

## Why local AI?

When you use a web-based AI chat, your text goes to the company's servers.
With local AI, the model runs on your own computer. No internet needed after
you download it. This is the safest option for anything involving member names,
emails, or dues.

## What you need

- A computer (Windows, Mac, or Linux)
- A few gigabytes of free disk space
- About 30 minutes to set up the first time
- No coding required

## Free local AI tools

| Tool | What it is | Best for |
|------|-----------|----------|
| Ollama | Runs AI models locally on your computer | General chat, drafting |
| Llama.cpp | Lightweight local model runner | Older computers |
| LM Studio | Easy desktop app for local models | Beginners who want a visual interface |

All are free to download and use.

## Step-by-step: try Ollama

### Step 1: Install Ollama

Go to ollama.com and download the installer for your computer. Follow the
on-screen instructions.

### Step 2: Download a model

Open your terminal or command prompt and run:

```
ollama run llama3.2
```

This downloads a small, capable model and starts a chat session.

### Step 3: Chat with your model

Type a prompt like:

```
Write a friendly reminder for our book club meeting next Tuesday.
Keep it short and warm. Do not use real member names.
```

The model responds entirely on your computer. Nothing is sent over the
internet.

### Step 4: Use it for club work

You can now draft agendas, newsletters, flyers, and more — all locally. When
you are done, close the terminal or type `/bye` to exit.

## Privacy reminder

Local AI is safer, but it is not magic. Do not paste sensitive member data
unless you trust your computer and its security. Keep backups. Use strong
passwords on your device.

## Credit

Written and published by **Asdale Dynamics, LLC** (Indiana). Plain-English AI
education for beginners, by Dylan Asdale.

MIT License. Copyright (c) 2026 Asdale Dynamics, LLC. See LICENSE.
