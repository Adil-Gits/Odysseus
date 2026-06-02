## 🚀 Setup Instructions (macOS)

Once you have installed the required software (Git, Python 3.11+, and Ollama), follow these steps to launch Odysseus AI on your Mac:

### Step 1: Clone and Launch Odysseus

1. Open your **Terminal** app (Press `Cmd + Space`, type "Terminal", and press Enter).
2. Copy and paste the following commands into the Terminal, then press **Return**:

```bash
git clone https://github.com/pewdiepie-archdaemon/odysseus.git
cd odysseus
chmod +x ./start-macos.sh
./start-macos.sh

```

> 💡 **Note:** Ensure you hit **Return** after the final line (`./start-macos.sh`) to execute the startup script. This script automatically handles your local virtual environment setup, installs dependencies, and runs the initial configuration.

---

### Step 2: Account Creation & Browser Launch

1. During the initial first-time setup process in the terminal, you will be prompted to configure an **ID and Password**.
2. Enter your desired credentials. Once complete, the local server will initialize.
3. Open your web browser and navigate to:
[http://localhost:7860](https://www.google.com/search?q=http://localhost:7860)
4. Log in using the credentials you just configured to access your Odysseus AI workspace.

---

### Step 3: Configure the Local AI Model

To utilize the full capabilities of your machine with local models (providing private alternatives to cloud services like GPT, Claude, or Gemini), connect a model via Ollama.

1. Keep your Odysseus server running, open a **new** Terminal window (`Cmd + N`), and execute:
```bash

```



ollama run opencoder

```
2. Allow a few minutes for the model files to download completely.
3. Once the download is finished, return to the Odysseus web interface and navigate to the built-in **Cookbook** section.
4. Run a system scan. Odysseus will automatically detect your active Ollama instance and integrate the `opencoder` model directly into your chat workflow.

```
