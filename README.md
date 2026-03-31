# 🐧 Open Source Software Scripts Collection

**Author:** Daksh Ahuja  
**Course:** Open Source Software  
**Reg No.:** 24BME10003

This repository contains a collection of Bash scripts designed to demonstrate key Linux system operations, open-source concepts, and automation techniques.

---

## 📂 Scripts Overview

### 1. 📊 System Identity Report (`script 1.sh`)
Generates a detailed report about the system and user environment.

**Features:**
- Displays Linux distribution name
- Kernel version
- Logged-in user
- Home directory
- System uptime
- Current date and time
- Open-source license message

**Usage:**
```bash
bash script\ 1.sh
```

---

### 2. 📦 FOSS Package Inspector (`script 2.sh`)
Checks whether a specific package (default: `git`) is installed and provides details.

**Features:**
- Verifies package installation using `dpkg`
- Displays installed version
- Provides a short description of popular open-source tools

**Usage:**
```bash
bash script\ 2.sh
```

---

### 3. 📁 Disk and Permission Auditor (`script 3.sh`)
Analyzes important system directories for permissions and disk usage.

**Features:**
- Checks directories like `/etc`, `/var/log`, `/home`, etc.
- Displays:
  - Permissions
  - Owner & group
  - Directory size
- Verifies existence of `.git` directory in home

**Usage:**
```bash
bash script\ 3.sh
```

---

### 4. 📜 Log File Analyzer (`script 4.sh`)
Searches log files for specific keywords and counts occurrences.

**Features:**
- Accepts log file as input
- Optional keyword argument (default: `"error"`)
- Counts keyword occurrences
- Displays last 5 matching lines

**Usage:**
```bash
bash script\ 4.sh <logfile> [keyword]
```

**Example:**
```bash
bash script\ 4.sh syslog warning
```

---

### 5. ✍️ Open Source Manifesto Generator (`script 5.sh`)
Generates a personalized open-source manifesto based on user input.

**Features:**
- Interactive input prompts
- Creates a manifesto text file
- Saves output as: `manifesto_<username>.txt`

**Usage:**
```bash
bash script\ 5.sh
```

---

## ⚙️ Requirements

- Linux-based system (Ubuntu/Debian recommended)
- Bash shell
- Basic utilities:
  - `dpkg`
  - `grep`
  - `awk`
  - `du`
  - `uname`

---

## 🚀 How to Run

1. Make scripts executable:
```bash
chmod +x *.sh
```

2. Run any script:
```bash
./script\ 1.sh
```

---

## 📌 Notes

- Scripts are designed for educational purposes.
- Some commands may require appropriate permissions.
- Ensure correct file paths when using the Log Analyzer.

---

## 🌍 Open Source Philosophy

These scripts highlight the power of open-source tools and Linux systems, promoting:
- Transparency
- Collaboration
- Accessibility

---

## 📧 Author

**Daksh Ahuja**  
Course: Open Source Software  
