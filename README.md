# 🤖 AutoTyper-HumanMode

**AutoTyper-HumanMode** is a smart Python-based typing automation tool that mimics **real human typing behavior** — including natural delays, typos, pauses, and distractions.  
It automatically types the contents of a `.txt` file into any active text field, appearing just like a real person typing.

---

## ✨ Features

- 🧠 **Human-like typing:** Randomized typing speed and natural pauses  
- 🕹️ **Hotkey controls:**  
  - `P` → Pause / Resume  
  - `Ctrl + Q` → Quit instantly  
- 🧍‍♂️ **“Human Mode” simulation:** Random thinking/distraction moments and small typos  
- 💻 **GUI interface:** Simple and minimal using Tkinter  
- ⚙️ **CPU-aware:** Pauses typing if CPU load is high  
- 📊 **Live status updates:** Characters typed, time elapsed, and typing status  

---

## 🧰 Requirements

- Python **3.8+**
- Install dependencies:

```bash
pip install psutil keyboard
(Tkinter and ctypes come preinstalled with Python.)

🚀 How to Use
1️⃣ Run the program
bash
Copy code
python autotyper.py
2️⃣ Load your text file
Click “Select File” → choose a .txt file with the text you want to auto-type.

3️⃣ Set start delay
Enter a delay (in seconds) before typing starts. Default is 5.

4️⃣ Start typing
Click “Start Typing” → switch to any window where you want the text to appear.
The program will begin typing automatically after the countdown.

⌨️ Hotkeys
Key	Action
P	Pause / Resume typing
Ctrl + Q	Quit immediately
Stop	Stop typing safely via GUI

🖥️ Example GUI
Window title:

Stealth Auto Typer - Human Mode (No Repeats)

Displays:

Status messages like “Typing...”, “Thinking...”, “Paused (Press P to Resume)”

Character count and time elapsed

Start/Stop buttons and file selector

📁 Project Structure
bash
Copy code
📦 AutoTyper-HumanMode/
├── autotyper.py        # Main script
├── README.md           # Documentation
└── requirements.txt    # Dependency list
⚡ Behavior Highlights
Typing speed varies between 0.22s – 0.36s per character

Random pauses and typos with auto-backspace correction

Small breaks to simulate “thinking” or “distraction” moments

Detects high CPU usage (>85%) and pauses until load drops
