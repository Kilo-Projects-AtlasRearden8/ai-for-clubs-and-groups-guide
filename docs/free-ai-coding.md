# Free AI Coding Tools for Club Organizers

A beginner guide to using free AI for small coding and automation tasks that
help clubs run more smoothly. No prior programming experience needed.

## Why coding helps clubs

Even a tiny bit of automation can save hours:

- Rename dozens of flyer files at once
- Convert a member list from one format to another
- Send the same email template to many people
- Create printable sign-up sheets from a spreadsheet

Free AI coding tools can write the code for you. You just copy, paste, and run.

## Free AI coding tools

| Tool | What it is | Cost |
|------|-----------|------|
| GitHub Copilot (free tier) | AI pair programmer in your editor | Free for verified students and open-source |
| Cursor (free tier) | AI-powered code editor | Free tier available |
| Web-based AI chat | Any free AI chat can write code snippets | Free |
| Local AI with code ability | Local models that write code | Free, runs on your machine |

## Step-by-step: rename files with AI help

Say you have 20 photos named `IMG_001.jpg`, `IMG_002.jpg`, etc., and you want
them named `plant-swap-01.jpg`, `plant-swap-02.jpg`, etc.

### Step 1: Ask the AI

Paste into a free AI chat:

```
Write a small Python script that renames all files in a folder from
IMG_001.jpg, IMG_002.jpg, etc. to plant-swap-01.jpg, plant-swap-02.jpg, etc.
Include comments explaining each line. Make it safe — do not delete anything,
just rename. Ask the user to confirm before making changes.
```

### Step 2: Copy the code

Copy the Python code the AI gives you. Save it as `rename_files.py`.

### Step 3: Run it

Open a terminal in the folder with your photos and run:

```
python rename_files.py
```

Review the changes before confirming. You are in control.

## Safety first

- Always test on copies, not your only files
- Read the code before running it
- If something looks wrong, ask the AI to explain or fix it
- Never paste real member names, emails, or addresses into coding prompts

## Credit

Written and published by **Asdale Dynamics, LLC** (Indiana). Plain-English AI
education for beginners, by Dylan Asdale.

MIT License. Copyright (c) 2026 Asdale Dynamics, LLC. See LICENSE.
