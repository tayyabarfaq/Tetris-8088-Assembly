# 🎮 Tetris in 8088 Assembly (16-bit)

This is a **fully functional Tetris game** written in **8088 Assembly language** for **16-bit DOS**. The game includes classic Tetris mechanics, colorful graphics drawn pixel by pixel, rotatable shapes, scoring system, countdown timer, and even a preview of the **next shape** — all coded from scratch using Assembly.

---

## 🕹️ How to Play

- Press `A` → Move Left  
- Press `D` → Move Right  
- Press `W` → Rotate Shape  
- Blocks fall automatically  
- The **left side of the screen shows the next incoming shape**

---

## 💡 Features

- ✅ Developed in **pure Assembly (NASM)** for 8088 16-bit architecture
- ✅ Rendered using **manual pixel-based graphics**
- ✅ **Rotatable blocks** with multiple shapes
- ✅ Real-time **scoring system**
- ✅ Countdown **timer system**
- ✅ **Preview of the next shape** 
- ✅ Intro and ending screens
- ✅ Color-coded Tetrimino blocks
- ✅ Written entirely using **Notepad++** and DOS graphics routines

---

## ⚙️ Requirements

- **DOSBox 0.74-3**
- **NASM assembler**
- **Notepad++** or any plain text editor for editing `.asm` file

---

## 🚀 How to Run (DOSBox Instructions)

> 💾 Make sure your `.asm` file is located in a folder like `C:\assmsoft` <br>
> this might take couple of minutes to load after step 3 and 4 

### Step-by-Step:

1. **Mount the directory** in DOSBox:
   ```dos
   mount c c:\assmsoft

2. **Change to mounted drive** in DOSBox:
   ```dos
   c:

3. **Assemble the code** in DOSBox:
   ```dos
   nasm mytetris.asm -o f.com

4. **Run the game** in DOSBox:
   ```dos
   f.com




  
