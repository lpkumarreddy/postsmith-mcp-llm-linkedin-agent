---

# 📸 MCP + LinkedIn: AI-Powered Post Creation via Cursor IDE

Create image-rich, high-impact LinkedIn posts directly from your IDE using MCP integration with Pipedream and Cursor. Automate post generation with custom images and text using natural language prompts — perfect for showcasing your work, event participation, or project launches.

---

## 🧰 Prerequisites

✅ Pipedream Account
✅ Authenticated LinkedIn Account
✅ Cursor AI Editor installed on:
  🪟 Windows
  🍎 macOS
  🐧 Ubuntu 24.04
✅ Basic understanding of IDE usage

---

## 🛠️ Cursor Installation & Setup

1️⃣ **Install Cursor AI Editor**
🪟 For Windows:
[Download Cursor for Windows](https://www.cursor.so/download)
[Watch YouTube Installation Tutorial](https://www.youtube.com/results?search_query=cursor+ide+installation)

🍎 For macOS:
[macOS Setup Guide](https://www.cursor.so/docs)

🐧 For Ubuntu 24.04:
[Ubuntu Setup Guide](https://www.cursor.so/docs)

✅ **Sign in** with Gmail or GitHub account
  After authentication in a browser tab, return to Cursor to continue.

---

## ⚙️ Initial Configuration in Cursor IDE

1️⃣ **Launch Cursor IDE**
2️⃣ On Welcome Screen:
  Click **Skip**, then **Continue** through:
  Theme • Quick Start • Data Sharing • Settings

---

## 🌐 MCP + LinkedIn Integration via Pipedream

### Step 1: Get MCP Server URL from Pipedream

* Go to [Pipedream](https://pipedream.com)
* Sign in / Sign up
* Search for **LinkedIn**
* Click **Connect Account** → Authenticate with LinkedIn
* Click on the **Cursor** tab
* Copy the **MCP Server URL**

⚠️ Do NOT share your Pipedream URLs — they include private auth tokens.

### Step 2: Add MCP Server to Cursor IDE

* Open Cursor → ⚙️ Settings → **Tools & Integrations**
* Click **Add Custom MCP**
* Paste the LinkedIn MCP Server URL
* Press `Ctrl + S` to save

---

## 🖼️ Prepare Your Image with Cloudinary

### Step 1: Upload Image

* Go to [Cloudinary Dashboard](https://cloudinary.com)
* Click **Assets** → **Assets Home**
* Hit **Upload** → Select image for your post

### Step 2: Get Image URL

* Go to **Folders** under Assets
* Right-click your image → **Copy URL**
* Click **Original** to get direct URL (⚠️ must be a direct `.jpeg` or `.png`)

---

## 🤖 Post Creation Workflow in Cursor IDE

### Step 1: Open the AI Panel

* Click **New Chat** (top-right)
* Or use shortcut: `Ctrl + Alt + B`

### Step 2: Paste This Prompt

```plaintext
Create an image post on LinkedIn with the following text:

I Built My AI Agent!  
Still can’t believe I created my own AI agent that works with Gmail, LinkedIn & more — all during the MCP Mega Workshop by NxtWave!  
From understanding how AI talks to tools to making it all work — I got to build, break, and learn.  
And that’s how this post happened 😉  
#mcpmegaworkshop #nxtwavemegaworkshop #ccbpacademy #nxtwaveacademy #MCP #AIWorkflows #FutureReady #StudentBuilders #TechWithImpact  

Image link: https://media-content.ccbp.in/ccbp_prod/media/misc/mcp_megaworkshop.jpeg
```

### Step 3: Submit Prompt

* Hit **Enter** to send
* Your LinkedIn post will be created in real-time 🎉
* Provide additional details if prompted by the agent

---

## ✅ Confirm Your Post on LinkedIn

Check your LinkedIn profile — your image + text post is now live and sharing your story with the world.

---

## 🔐 Security & Best Practices

* Keep Pipedream URLs **private**
* Use **Cursor logs** and **Pipedream logs** for debugging
* Want to integrate GitHub, Gmail, or YouTube too? Just repeat the MCP setup flow

---

## 📄 License

**MIT License**

```
MIT License

Copyright (c) 2025 lpkumarreddy

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

---

## 🙌 Acknowledgements

Huge thanks to the **Cursor IDE** and **Pipedream** teams for building the infrastructure that enables seamless AI-driven automation — and to **NxtWave** for pioneering real-world AI education through the **MCP Mega Workshop**.
