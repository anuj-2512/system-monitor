# 🖥️ Linux System Monitor Tool

A **real-time system monitoring tool** built in **C++**, inspired by the Linux `top` command.  
This tool displays live information about system processes, CPU usage, and memory utilization using the `/proc` filesystem and an `ncurses`-based text user interface.

---

## 🚀 Features

- 📊 Real-time CPU usage (overall percentage)
- 💾 Memory usage (total, used, percentage)
- ⚙️ Live process list (PID, user, CPU%, MEM%, RSS, command)
- 🔢 Sorted by CPU usage (highest first)
- 🕒 Auto-refresh every second
- 🎛️ Simple controls (`q` to quit)
- 🧠 Lightweight and written in pure C++17 using `ncurses`

---

## 🧩 Technologies Used

- **C++17**
- **Linux `/proc` filesystem**
- **Ncurses** for text-based UI
- **System calls and process management**

---

## 📁 Project Structure

