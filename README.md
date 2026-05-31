# Digital Marketing Pro "v4.0.0" — WhatsApp Marketing & Automation

Desktop Application

Digital Marketing Pro is a production-grade desktop automation tool designed to streamline lead generation, automate messaging workflows, and manage community growth on WhatsApp efficiently. Built using Electron, Node.js, and Express, it features robust state handling and anti-detection mechanisms.

---

## 🔒 License & Usage Restrictions

**Proprietary / Private Use Only**

Copyright (c) 2026 Janaka Prageeth. All rights reserved.

- **Allowed:** Personal evaluation, private study, and non-commercial testing.
- **Strictly Prohibited:** Commercial usage, redistribution, sub-licensing, reselling, or public deployment of this software.
---

## 🚀 Key Features

- **Multi-Account & Session Management:** Register, switch, and manage multiple WhatsApp profiles securely using multi-file authentication states.
- **Group Contact Extractor (Scraper):** Extract and resolve participant data (including real-time LID-to-phone mappings) from connected groups and export directly to Excel/CSV.
- **Bulk Marketing Messenger:** High-volume automated message broadcasting featuring randomized delay algorithms to mimic human behavior and minimize ban rates.
- **Automated Group Builder:** Smart continuous session handler to add external contacts into specific WhatsApp groups while auto-routing privacy-restricted users via targeted DM invites.
- **Security & Anti-Piracy:** Integrated with machine HWID verification, custom obfuscated production pipelines (via AST transformation), and context-isolated UI environments to protect core logic.

---

## 🛠️ Architecture & Tech Stack

- **Frontend:** HTML5, CSS3 (Modern Glassmorphic UI Dashboard), Vanilla JavaScript (IPC Integration).
- **Desktop Wrapper:** Electron (Context Isolation, Custom Titlebars, Utility Processes).
- **Backend Core:** Node.js, Express.js, Local JSON Database.
- **Protocols & Drivers:** Baileys (Multi-Device API WhatsApp Web protocol) & WhatsApp-Web.js (Puppeteer headless browser automation).
- **Security & Obfuscation:** JavaScript-Obfuscator, Node-Machine-Id, @electron/asar.

---

## 💻 Technical Implementation Details

### 1. Inter-Process Communication (IPC)
The application leverages Electron's secure IPC layers to bridge the rendering context with a localized Express backend server, ensuring no exposure of raw Node.js capabilities to the user interface.

### 2. Anti-Ban Delay Pipeline
To safeguard user accounts, bulk messaging tasks utilize an asynchronous queue system equipped with dynamic, randomized millisecond delays that effectively bypass traditional automated behavioral tracking.

### 3. Production Build Obfuscation
The deployment workflow incorporates an automated build script that applies advanced AST transformations (Control Flow Flattening, Dead Code Injection, String Array Encryption) to the codebase right before compiling it into an enclosed `.asar` archive.

---

## 📦 Local Installation & Setup

> **Note:** This installation guide is intended for local development and private evaluation purposes only.

### Prerequisites
- [Node.js](https://nodejs.org/) (v16.x or higher recommended)
- npm (comes bundled with Node.js)

### Step-by-Step Setup

1. **Clone the Repository:**
```bash 
git clone https://github.com/VishwaDasun/Digital-Marketing-Manager-Pro.git
cd Digital-Marketing-Manager-Pro

