<h1 align="center">🧩 FEX GUI CHECKER</h1>
<p align="center">
  <b>A modern CustomTkinter-based GUI checker with glossy dark UI, proxy support, and high-performance HTTPX threading.</b><br>
  <sub>Built with ❤️ using Python 3.10+, CustomTkinter, and HTTPX 0.28.1</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/CustomTkinter-Dark%20UI-black?logo=windowsterminal" alt="CustomTkinter">
  <img src="https://img.shields.io/badge/HTTPX-0.28.1-orange?logo=fastapi" alt="HTTPX">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
</p>

---

### 🚀 Features
- 🌑 **Glassy dark CustomTkinter UI**
- 🔁 **Multi-threaded** execution using `ThreadPoolExecutor`
- ⚡ **HTTPX 0.28.1** networking with full **proxy support**
  - Supports `ip:port` and `ip:port:user:pass` raw formats
- 🧠 Smart **auto proxy converter** → `http://user:pass@ip:port`
- 📊 Real-time **CPM counter**, progress bar, and hits counter
- 🧾 **Export results** to `./Results/hits.txt`
- 🎨 Includes **Credits window** with clickable YouTube, Telegram, and Facebook buttons
- 💪 Built with **Nuitka** for high-speed standalone `.exe` packaging

---

### 🧠 How It Works
The tool loads combo and proxy lists, performs asynchronous login checks against the FEX API, and extracts detailed account data such as:
- Token  
- Plan name (Trial or Premium)  
- Storage usage  
- Country  

---

### 🖥️ Screenshots
<p align="center">
  <img width="1413" height="828" alt="Screenshot 2025-11-01 190556" src="https://github.com/user-attachments/assets/1c798a21-bd94-4588-951d-1f04db257f98" />
</p>

---

### ⚙️ Build Instructions (with Nuitka)
```bash
pip install nuitka customtkinter httpx
