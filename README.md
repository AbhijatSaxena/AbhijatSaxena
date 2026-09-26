<p align="center">
  <img src="assets/hero-dark.svg#gh-dark-mode-only" alt="Abhijat Saxena" />
  <img src="assets/hero-light.svg#gh-light-mode-only" alt="Abhijat Saxena" />
</p>

<p align="center">
  <img src="assets/typing-dark.svg#gh-dark-mode-only" alt="typing animation" />
  <img src="assets/typing-light.svg#gh-light-mode-only" alt="typing animation" />
</p>

---

## 🔨 Featured Projects

<sub>Click any project to expand it 👇</sub>

<details>
<summary><b>blink-camera-mcp</b> — an MCP server for Amazon Blink cameras, including the pan/tilt mount</summary>
<br>
Blink exposes no local API, no ONVIF, no UVC — video only as a 300-second cloud-brokered session. The pan/tilt accessory has no endpoint of its own: it is driven <i>inside</i> the camera's media session, and its position returns on the same socket, which is why a client that reads only video frames never sees the mount's traffic at all.
<br><br>
This server owns that session, frames it correctly, routes the accessory messages, and exposes the whole thing as MCP tools with closed-loop semantics — <code>pan_tilt</code>, <code>pan_tilt_nudge</code>, <code>pan_tilt_overview</code> (360° sweep), <code>snapshot</code>, and more. 2FA codes are read once from a file and deleted, so a live credential never lands in shell history or a chat log.
<br><br>
Published to PyPI and listed in the official MCP Registry as <code>io.github.AbhijatSaxena/blink-camera-mcp</code>.
<br><br>
<code>Python</code> <code>MCP</code> <code>asyncio</code> <code>GitHub Actions</code>
<br><br>
<a href="https://github.com/AbhijatSaxena/blink-camera-mcp">→ View on GitHub</a> · <a href="https://pypi.org/project/blink-camera-mcp/">→ PyPI</a>
</details>

<details>
<summary><b>phoenix</b> — a self-hosted personal finance dashboard</summary>
<br>
Net worth across liquid, appreciating, and depreciating assets, with automatic multi-currency conversion (USD/CAD/INR) on live rates. Derived accounts — property equity, stock portfolio, car value — are computed from their own pages and feed the dashboard back automatically.
<br><br>
Daily snapshots with trend charts and notes, per-currency budget tracking with drag-and-drop line items, a property tracker with configurable rate parameters and EMI history, and a Zerodha portfolio page covering equity, F&amp;O, commodities, and mutual funds. Role-based access with remote session revocation.
<br><br>
<code>React 18</code> <code>TypeScript</code> <code>Vite</code> <code>MUI v9</code> <code>Zustand</code> <code>Firebase</code> <code>Recharts</code>
<br><br>
<a href="https://github.com/AbhijatSaxena/phoenix">→ View on GitHub</a>
</details>

<details>
<summary><b>ADHDoit</b> — a todo app built for ADHD brains</summary>
<br>
A dependency graph links todos so blocked tasks surface visually, laid out as a DAG with dagre. Focus mode gives you one task at a time with a timer synced to Firestore, so it survives switching devices mid-session.
<br><br>
Describe a task in plain language and get structured todos back via Groq (Llama 3.3-70B). Per-task comments, a done/archived split, remote session revocation, and an admin panel for users and todos.
<br><br>
<code>React 18</code> <code>TypeScript</code> <code>Vite</code> <code>MUI v9</code> <code>Zustand</code> <code>Firebase</code> <code>Groq</code>
<br><br>
<a href="https://github.com/AbhijatSaxena/ADHDoit">→ View on GitHub</a> · <a href="https://adhdoitapp.web.app">→ Live</a>
</details>

<details>
<summary><b>…and more</b></summary>
<br>
Fork trees I contribute back to rather than just clone:
<br><br>
<code>fronzbot/blinkpy</code> — <a href="https://github.com/fronzbot/blinkpy/pull/1318">#1318</a> adds the IMMI accessory channel helpers the pan/tilt mount protocol needs
<br>
<code>punkpeye/awesome-mcp-servers</code> — <a href="https://github.com/punkpeye/awesome-mcp-servers/pull/15145">#15145</a> lists blink-camera-mcp
<br>
<code>NousResearch/hermes-agent</code> — provider-registration and managed-env fixes
</details>

---

## 📦 Open Source Footprint

- **`blink-camera-mcp` published** to PyPI and the official MCP Registry — a real, installable `uvx` server, not a demo
- **Open upstream PRs** in libraries I depend on: [fronzbot/blinkpy#1318](https://github.com/fronzbot/blinkpy/pull/1318) (pan/tilt protocol helpers) and [punkpeye/awesome-mcp-servers#15145](https://github.com/punkpeye/awesome-mcp-servers/pull/15145)
- **Bug fixes to agent tooling** in [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent/pulls?q=is%3Apr+author%3AAbhijatSaxena) — provider alias registration, managed-Python env handling

Every project above is something I use myself. That is usually why it got built.

---

## 🛠 Stack

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/MUI-007FFF?style=flat-square&logo=mui&logoColor=white" alt="MUI" />
  <img src="https://img.shields.io/badge/MCP-1a1442?style=flat-square&logoColor=white" alt="MCP" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

Full-stack web · Agent tooling &amp; MCP servers · Home automation · Firebase · Self-hosted everything

<p align="center"><sub><code>♥JavaScript♥</code></sub></p>
