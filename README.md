# ⌨️ Bash `read` Command — Accept User Input in Shell Scripts (2026)

![Linux](https://img.shields.io/badge/Linux-Guide-blue)
![Level](https://img.shields.io/badge/Level-Beginner%20to%20Intermediate-green)
![Updated](https://img.shields.io/badge/Updated-2026-orange)
![Focus](https://img.shields.io/badge/Focus-User%20Input-important)

> Want interactive Bash scripts that accept user input?  
> The `read` command is the foundation of user interaction in shell scripting.

📖 **[Full Guide (syntax + examples + interactive scripts → linuxteck.com)](https://www.linuxteck.com/bash-read-command-user-input-examples/?utm_source=github&utm_medium=repo&utm_campaign=read-command)**

---

## ⚡ 1-Minute Understanding

If you remember just this:

- `read` captures keyboard input  
- Stores values in variables  
- Used in interactive scripts and automation  

💡 Without `read`, scripts can’t interact with users.

---

## 🖼️ Preview

> Interactive Bash script using the `read` command

![Preview](https://raw.githubusercontent.com/linuxteck/bash-read/main/read-preview.png)

---

## 🧠 Why This Guide Exists

Most beginners learn Bash output first (`echo`) — but not input.  
The `read` command unlocks interactive scripting.

This guide helps you:
- Accept user input in scripts  
- Use prompts and hidden passwords  
- Build practical interactive tools  

---

## 🔄 Common read Examples

| Command | What It Does |
|---------|--------------|
| `read name` | Store user input in variable |
| `read -p` | Show prompt message |
| `read -s` | Hide typed input |
| `read -t` | Set timeout |
| `read -a` | Store input into array |

---

## 👉 Want full examples and advanced usage?  
Read here:  
https://www.linuxteck.com/bash-read-command-user-input-examples/?utm_source=github&utm_medium=repo

---

## 🚀 Quick Practice (Copy-Paste Ready)

```bash
# Simple input
read name
echo "Hello $name"

# Input with prompt
read -p "Enter your username: " user

# Hidden password input
read -s -p "Password: " pass
echo
```

---

## 🧪 Example Interactive Script

```bash
#!/bin/bash

read -p "What is your name? " name

echo "Welcome, $name!"
```

---

## 🎯 When Should You Use read?

```bash
# Interactive shell scripts
# Login prompts
# Automation tools
# User-driven workflows
```

---

## 🎯 Who Gets the Most Value

| You Are | Benefit |
|---------|--------|
| 🟢 Beginner | Learn interactive scripting |
| 🔵 Sysadmin | Build smarter scripts |
| 🔴 DevOps Engineer | Improve automation tools |
| 🟡 Developer | Create user-friendly CLI tools |

---

## 🔗 More LinuxTeck Guides You'll Want

> 📂 *Part of the **LinuxTeck Master Series** — practical Linux guides*

- ⚡ https://www.linuxteck.com/modern-linux-tools/
- 📊 https://www.linuxteck.com/linux-logging-best-practices/
- 🔐 https://www.linuxteck.com/uefi-secure-boot-linux/
- 🔤 https://www.linuxteck.com/sort-command-in-linux/
- 🔍 https://github.com/linuxteck?tab=repositories

---

## ✍️ About LinuxTeck

**https://www.linuxteck.com** publishes practical, real-world Linux guides — no fluff, no filler.  
If you're learning shell scripting, these guides will save you hours.

⭐ Found this useful? Star this repo — it helps more learners discover it  
🔁 Share with your friends — especially if they’re learning Bash 😄  
👤 https://github.com/linuxteck

---

**Topics:** bash • read-command • shell-scripting • linux • scripting • automation • terminal • devops • sysadmin • beginner
