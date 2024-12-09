# Obedient Cat - picoCTF Challenge 🚀🐾

**Version**: 1.0  
**Author**: [Trung Huynh](https://www.linkedin.com/in/trung-huynh-chi-pc01/)  

![Challenge](https://img.shields.io/badge/Challenge-picoCTF-blue?style=for-the-badge&logo=codeforces&logoColor=white)  
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge&logo=open-source-initiative&logoColor=white)  
![Contributions](https://img.shields.io/badge/Contributions-Welcome-orange?style=for-the-badge&logo=github&logoColor=white)  

---

## 📜 Challenge Description
The task requires downloading a file and using basic Linux commands to retrieve the flag.

---

## 🛠️ Steps to Solve
![Local Image](img/Obedient_Cat/h1.png "Local Image")
1. **Download the file:**
   ```bash
   wget https://mercury.picoctf.net/static/fb851c1858cc762bd4eed569013d7f00/flag
   ```
   This command downloads the file named `flag` from the provided URL.

2. **List the downloaded file:**
   ```bash
   ls
   ```
   Ensure the `flag` file is in the current directory.

3. **Read the contents of the file:**
   ```bash
   cat flag
   ```
   Output:
   ```
   picoCTF{s4n1ty_v3r1f13d_28e8376d}
   ```
   ![Local Image](img/Obedient_Cat/h2.png "Local Image")
---

## 🎯 Flag
```
picoCTF{s4n1ty_v3r1f13d_28e8376d}
```

---

## 💡 Key Takeaway
This challenge demonstrates the importance of knowing basic Linux commands like `wget`, `ls`, and `cat` for handling files and solving CTF tasks.


