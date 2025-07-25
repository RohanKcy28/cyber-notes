
---

## 🔹 `level-1.md`

### ✅ Bandit Level 1 → Level 2

**🧠 Level Goal:**  
The password for the next level is stored in a file called `-` located in the home directory.

**🔧 Commands Used:**
ls -al
cat ./-


**🖥️ Steps:**

ssh bandit1@bandit.labs.overthewire.org -p 2220
# password: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
ls -al
cat ./-

🔑 Password for bandit2:
263JGJPfgU6LtdEvgfWU1XP5yac29mFx

📌 Notes:

A filename - confuses the cat command.

Prefixing with ./ tells the shell it’s a file in the current directory (cat ./-).
