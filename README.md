# 🚩 picoCTF: Beginner's Guide to the Challenge Library

Welcome to my writeup repository and notes collection for **The Beginner's Guide to the Challenge Library** path on [picoCTF](https://picoctf.org/). 

This repository documents my progress, command workflows, key takeaways, common mistakes, and reusable scripts across all 28 solved challenges.

---

## 📂 Repository Contents

- **[`notes.md`](./notes.md)** – Complete master notes, category-wise breakdowns, solution methods, and common beginner mistakes.
- **`28 Solved Challenges`** – Full execution steps covering Linux CLI, Binary Inspection, Base Conversions, Python Scripting, Web Exploitation, and Reverse Engineering.

---

## 🛠️ Core Topics Covered

1. **General Skills:** Linux CLI navigation, tab completion, environment variables, piping, `grep`, and `strings`.
2. **Web Exploitation:** Client-side source code inspection (HTML/CSS/JS), cookie manipulation, and HTTP request headers.
3. **Cryptography & Data:** Base64, Hexadecimal, ASCII conversions, and raw data transformations using CyberChef.
4. **Forensics & Reversing:** File headers, metadata extraction, Python hardcoded check reversing, and Java decompilation.

---

## 🚀 Quick Commands Checklist

```bash
# Extract readable strings from binary files
strings <file> | grep "picoCTF"

# Search subfolders recursively
grep -rn "picoCTF" .

# Decode Base64
echo "<base64_string>" | base64 -d

# Netcat Connection
nc <host> <port>
