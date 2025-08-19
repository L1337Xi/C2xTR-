# C2xTR
Custom Command &amp; Control Framework
# ⚔️ C2xTR – Command & Control Framework

**C2xTR** is a custom-built, Python-based Command and Control (C2) framework designed for red team operations, offensive security labs, and post-exploitation simulation. It allows security professionals and enthusiasts to manage multiple reverse shell sessions across different target machines, execute commands interactively, and simulate real-world adversary behaviors.

---

## 📌 Features

- 🔄 Connect to multiple compromised machines simultaneously
- 💻 Interactive shell for each target or all at once
- 🧠 Multi-threaded architecture for efficient communication
- 🔒 Simple socket-based secure communication
- 📂 Add/remove/list targets dynamically
- 🔎 Target shell command execution with output handling

---

## 🧱 Architecture Overview

- **`c2xi.py`** – The main C2 controller script (run on the attacker's server).
- **`C2xTR.py`** – The implant/agent to be deployed on each target system.

- ## 🛠️ Installation
- Clone the Repository
- git clone https://github.com/L1337Xi/C2xTR.git
- cd C2xTRr




-  

-  🖥️ Start the C2 Controller
-  You will be presented with a command-line menu to manage connections.

