# 💻 Cyber Terminal Portfolio  

> A futuristic hacker-style terminal portfolio — complete with Matrix rain, glitch effects, typewriter sounds, and interactive commands.  
> Built with pure **HTML, CSS, and JavaScript** — no frameworks, no dependencies, just vibes.  

---

## 🧠 Overview  

**Cyber Terminal** is an interactive portfolio concept that mimics a hacker’s console.  
It boots up with a Matrix-like animation, reveals your profile through a typing sequence,  
and then lets visitors explore using real terminal commands.  

⚡️ Demo: [Live Preview](https://your-demo-link.com)  

---

## ✨ Features  

- 🟩 **Matrix Rain Animation** — rendered on a live `<canvas>` background  
- 💬 **Typewriter Intro Sequence** — complete with sound effects  
- 🧩 **Interactive Command System** (`help`, `about`, `skills`, `projects`, etc.)  
- ⚡️ **Glitch Header Effect** (`akshat@matrix`)  
- 🎧 **Type & Error Sounds** for realistic UX  
- 🕶️ **Floating 3D Terminal UI** with neon glow aesthetics  
- 🕒 **Live Clock** inside the header  
- 📱 **Fully client-side & framework-free**

---

## 🚀 Quick Start  

### 1️⃣ Clone this repo  
```bash
git clone https://github.com/your-username/cyber-terminal-portfolio.git
cd cyber-terminal-portfolio
2️⃣ Run locally
Simply open index.html in your browser.
No setup required. No build tools.

3️⃣ (Optional) Deploy
Use any static host:

Vercel

Netlify

GitHub Pages

🧾 Available Commands
Command	Description
help	List available commands
about	Shows personal info
skills	Displays skillset
projects	Lists portfolio projects
contact	Shows contact & socials
resume	Opens resume link
clear	Clears the terminal
exit	Funny response 😉

🧰 Customization Guide
You can easily make this terminal your own — no frameworks, no config mess.

🧑‍💻 Edit the Intro Text
Open index.html → scroll to the “Typing effect messages” section.
You’ll see a JS array like this:

js
Copy code
const messages = [
  { text: "Initializing system...", delay: 50 },
  { text: "> Welcome to CYBER TERMINAL // ACCESS GRANTED", delay: 10, style: "color:#0f0; font-weight:bold" },
  { text: "> NAME: Akshat", delay: 80, style: "color:#0ff" },
  // ...
];
Change the text and colors however you want — emojis, delays, or your own intro lines.

⚙️ Edit Commands
Scroll to the processCommand() function inside <script> —
you’ll see command blocks like this:

js
Copy code
else if (command === 'about') {
  response.innerHTML = `I'm a Computer Science undergrad exploring web dev and AI.`;
}
You can add or remove commands — for example:

js
Copy code
else if (command === 'funfact') {
  response.innerHTML = `I can code faster than my Wi-Fi loads 😎`;
}
🎨 Customize Theme Colors
In the CSS section (<style>), tweak the color variables at the top:

css
Copy code
:root {
  --terminal-bg: #0a0a12;
  --terminal-green: #0f0;
  --terminal-cyan: #0ff;
  --terminal-purple: #b19cd9;
}
Change them to whatever palette you like — purple cyberpunk? blue neon? dark red hacker theme? All possible.

🔊 Replace Sounds
The two <audio> tags near the end handle typing and error sounds.
You can replace their links with your own MP3s or custom effects.

html
Copy code
<audio id="type-sound" src="assets/type.mp3"></audio>
<audio id="error-sound" src="assets/error.mp3"></audio>
🧱 Add Your Resume
In the resume command section:

js
Copy code
else if (command === 'resume') {
  response.innerHTML = `<a href="https://your-resume-link.pdf" target="_blank">Open Resume</a>`;
}
💬 Add New Project or Skill
Inside the projects or skills command, just add more <br> lines —
it’s plain HTML inside a string.

🌍 Deploy Example (GitHub Pages)
Push to a GitHub repo

Go to Settings → Pages → Source → Deploy from branch

Select main branch → /root

Done. Your link will look like:
https://your-username.github.io/cyber-terminal-portfolio/

🧑‍💻 Contributing
Pull requests are welcome!
If you build a cooler version — add new commands, animations, or easter eggs —
drop a PR or share it with #cyber-terminal tag on X/LinkedIn.

📜 License
This project is licensed under the MIT License — feel free to use, remix, or rebuild it for your own portfolio.
Just drop a credit or star the repo ⭐ if you find it useful!

👾 Created by Akshat Rathore
“Access Granted. Welcome to the Matrix.”

yaml
Copy code

---

If you want, I can also make a **README version with emojis and visuals (like screenshot section + preview GIF)** to make it look even more “GitHub Trending–ready.”  
Want me to make that next?






You said:
now give me final readme in copy-paste format



ChatGPT said:
Absolutely 🔥 — here’s your final, copy-paste-ready README.md, perfectly formatted for GitHub with emojis, visuals, customization guide, and everything a trending repo needs 👇

markdown
Copy code
# 💻 Cyber Terminal Portfolio  

> A futuristic hacker-style terminal portfolio — complete with Matrix rain, glitch effects, typewriter sounds, and interactive commands.  
> Built with pure **HTML, CSS, and JavaScript** — no frameworks, no dependencies, just vibes.  

---

## 🧠 Overview  

**Cyber Terminal** is an interactive portfolio concept that mimics a hacker’s console.  
It boots up with a Matrix-like animation, reveals your profile through a typing sequence,  
and then lets visitors explore using real terminal commands.  

⚡️ **Live Demo:** [your-demo-link-here](https://your-demo-link-here.com)  

---

## ✨ Features  

- 🟩 **Matrix Rain Animation** — rendered on a live `<canvas>` background  
- 💬 **Typewriter Boot Sequence** — with authentic typing sounds  
- 🧩 **Interactive Command System** (`help`, `about`, `skills`, `projects`, etc.)  
- ⚡️ **Glitch Text Header** (`akshat@matrix`)  
- 🎧 **Type & Error Sounds** for realistic UX  
- 🕶️ **Floating 3D Terminal UI** with neon glow effects  
- 🕒 **Live Clock** inside the header  
- 📱 **Fully client-side & framework-free**

---

## 🚀 Quick Start  

### 1️⃣ Clone this repo  
```bash
git clone https://github.com/your-username/cyber-terminal-portfolio.git
cd cyber-terminal-portfolio
2️⃣ Run locally
Just open index.html in your browser — no setup or installation required.

3️⃣ (Optional) Deploy
You can host it instantly on:

Vercel

Netlify

GitHub Pages

🧾 Commands
Command	Description
help	List available commands
about	Shows personal info
skills	Displays skillset
projects	Lists portfolio projects
contact	Shows contact & socials
resume	Opens resume link
clear	Clears the terminal
exit	Funny response 😉

🧰 Customization Guide
Easily make this terminal your own — no frameworks, no config mess.

🧑‍💻 Edit the Intro Text
Inside index.html, find the "Typing effect messages" section:

js
Copy code
const messages = [
  { text: "Initializing system...", delay: 50 },
  { text: "> Welcome to CYBER TERMINAL // ACCESS GRANTED", delay: 10, style: "color:#0f0; font-weight:bold" },
  { text: "> NAME: Akshat", delay: 80, style: "color:#0ff" },
  // ...
];
Change the text, emojis, colors, or delays to personalize your intro.

⚙️ Edit or Add Commands
Inside the processCommand() function:

js
Copy code
else if (command === 'about') {
  response.innerHTML = `I'm a Computer Science undergrad exploring web dev and AI.`;
}
Add your own like this:

js
Copy code
else if (command === 'funfact') {
  response.innerHTML = `I can code faster than my Wi-Fi loads 😎`;
}
🎨 Customize Theme Colors
In the CSS section (<style>), tweak the root variables:

css
Copy code
:root {
  --terminal-bg: #0a0a12;
  --terminal-green: #0f0;
  --terminal-cyan: #0ff;
  --terminal-purple: #b19cd9;
}
Switch them up to create your own theme — purple cyberpunk, blue neon, etc.

🔊 Replace Sound Effects
At the end of index.html, you’ll find:

html
Copy code
<audio id="type-sound" src="assets/type.mp3"></audio>
<audio id="error-sound" src="assets/error.mp3"></audio>
Swap in your own .mp3 files or sound URLs.

📄 Add Your Resume
Inside the resume command section:

js
Copy code
else if (command === 'resume') {
  response.innerHTML = `<a href="https://your-resume-link.pdf" target="_blank">Open Resume</a>`;
}
🧱 Add New Projects or Skills
Just edit the text inside the projects or skills command section —
it’s plain HTML inside strings. Example:

js
Copy code
else if (command === 'projects') {
  response.innerHTML = `[2025] Chillomo — A Lofi Study Sanctuary<br>[2025] InstantLanding — One-click landing pages<br>[2024] DailyLift — AI-Generated Quotes`;
}
🌍 Deploy Example (GitHub Pages)
Push your project to GitHub

Go to Settings → Pages → Source → Deploy from branch

Choose main branch → /root

Done 🎉
Your site will be live at:
https://your-username.github.io/cyber-terminal-portfolio/

🧑‍💻 Contributing
Pull requests are welcome!
If you add new commands, animations, or easter eggs — share them via a PR or post on socials with the tag #CyberTerminal 🚀

📜 License
This project is licensed under the MIT License — free to use, remix, or build on.
If you find it cool, drop a ⭐ on the repo or tag me when you fork it!

👾 Creator
Built by Akshat Rathore

“Access Granted. Welcome to the Matrix.”

yaml
Copy code

---

If you want, I can also add a **screenshot + preview GIF section** (for GitHub visuals) —  
wanna include that too before you upload it?
