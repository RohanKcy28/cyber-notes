
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
# password: [REDACTED — saved locally]
ls -al
cat ./-

🔑 Password for bandit2:
[REDACTED — saved locally]

📌 Notes:

A filename - confuses the cat command.

Prefixing with ./ tells the shell it’s a file in the current directory (cat ./-).
