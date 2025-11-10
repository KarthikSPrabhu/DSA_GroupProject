# 🏥 Smart Hospital System

The **Smart Hospital System** is a C-based program that simulates hospital management and analysis.  
It reads data from a text file (`database.txt`) and provides information about hospitals, areas, and distances between them.  

---

## 📁 Project Structure

📦 Smart-Hospital-System
├── main.c
├── smart_hospital.c
├── smart_hospital.h
├── database.txt
└── README.md


---

## ⚙️ Features

- Reads hospital and area data from a text file  
- Displays hospital details, areas, and distance matrices  
- Calculates optimized distances between hospitals and areas  
- Modular C design using header and source files  

---

## 🧩 Requirements

Make sure you have a C compiler installed.  
You can use any of the following:

- **Linux / macOS:** `gcc` (preinstalled or install via `sudo apt install build-essential`)
- **Windows:** [MinGW](https://sourceforge.net/projects/mingw/)

---

## 🚀 How to Compile and Run

### 🖥️ On Linux / macOS

```bash
# Step 1: Compile the program
gcc -std=c11 -Wall -Wextra -o smart_hospital main.c smart_hospital.c

# Step 2: Run the program
./smart_hospital
