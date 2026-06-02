# Odysseus AI Setup Guide (Windows & Mac)

This repository provides a step-by-step guide on how to install and run **Odysseus AI** locally on your machine. Follow the instructions below to get everything up and running.

---

## 🛠️ Downloads (IMPORTANT)

Before installing Odysseus AI, you **must** download and install the following core dependencies. Choose the links corresponding to your operating system.

### 1. Git / Git Bash
Required to clone this repository and manage version control.
* **Windows:** Download [Git for Windows](https://git-scm.com/download/win) (This includes **Git Bash**, which is highly recommended for running commands).
* **Mac:** Download [Git for Mac](https://git-scm.com/download/mac) (or install via Homebrew using `brew install git`).

### 2. Python (v3.10 or higher recommended)
The core programming language used to run Odysseus AI.
* **Windows & Mac:** Download the latest stable version from the [Official Python Website](https://www.python.org/downloads/).
> ⚠️ **Important (Windows Users):** During installation, make sure to check the box that says **"Add Python.exe to PATH"** before clicking install.

### 3. Ollama
Used to run large language models (LLMs) locally on your hardware.
* **Windows & Mac:** Download and install from [Ollama's Official Website](https://ollama.com/).
* *After installing, verify it works by opening your terminal/Git Bash and running:*
    ```bash
    ollama --version
    ```

---

## 🚀 Setup Instructions (Windows)

Once you have installed the required software (Git/Git Bash, Python, and Ollama), follow these steps to launch Odysseus AI:

### Step 1: Clone and Launch Odysseus

1. Open **Windows PowerShell** (Search for "PowerShell" in your Windows start menu).
2. Copy and paste the following commands into PowerShell, then press **Enter**:

```powershell
git clone https://github.com/pewdiepie-archdaemon/odysseus.git
cd odysseus
powershell -ExecutionPolicy Bypass -File .\launch-windows.ps1

```

> 💡 **Note:** Ensure you hit **Enter** after the final script line (`.\launch-windows.ps1`) to trigger the installer. The script will automatically download and configure the remaining files needed for Odysseus.

---

### Step 2: Account Creation & Browser Launch

1. Once the installation completes, the terminal will prompt you to create an **ID and Password**.
2. Enter your credentials. The script will then spin up a local server.
3. Open your web browser and navigate to:
[http://localhost:7000](https://www.google.com/search?q=http://localhost:7000)
4. You should see the Odysseus AI login page. Log in using the credentials you just created.

---

### Step 3: Configure the Local AI Model

To get the full benefits of the platform (similar to GPT, Claude, or Gemini models), you need to connect a local model via Ollama.

1. Keep your server running, open a **new** PowerShell window, and run:
```powershell

```



ollama run opencoder

```
2. Wait a few minutes for the model to finish downloading.
3. Once the download completes, navigate to the built-in **Cookbook** feature inside the Odysseus web interface.
4. Run the system scan. Odysseus will automatically detect your local Ollama server and link the `opencoder` model directly into your chat interface.
5. You can then enjoy using the AI.
```
