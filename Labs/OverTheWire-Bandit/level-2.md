

## 🔹 `level-2.md`

### ✅ Bandit Level 2 → Level 3

**🧠 Level Goal:**  
The password for the next level is stored in a file called `spaces in this filename` in the home directory.

**🔧 Commands Used:**
ls -al
cat "spaces in this filename"

**🖥️ Steps:**

ssh bandit2@bandit.labs.overthewire.org -p 2220
# password: [REDACTED — saved locally]
ls -al
cat "spaces in this filename"

🔑 Password for bandit3:
[REDACTED — saved locally]

📌 Notes:
Filenames with spaces must be wrapped in quotes (" ") or escaped (\ ).
