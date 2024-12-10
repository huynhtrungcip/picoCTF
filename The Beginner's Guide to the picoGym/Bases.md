# 🌌 **Bases - picoCTF Challenge** 🚀🔐

![Cryptography](https://img.shields.io/badge/Tool-Cryptography-blue?style=for-the-badge&logo=google-scholar&logoColor=white)  
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge&logo=open-source-initiative&logoColor=white)  
![Contributions](https://img.shields.io/badge/Contributions-Welcome-orange?style=for-the-badge&logo=github&logoColor=white)  

---

## 📋 **Challenge Overview**  

Welcome to the **picoCTF** cryptography challenge **"Bases"**!  
You are provided with the encoded string: 
```bash 
bDNhcm5fdGgzX3IwcDM1
```

The hint suggests this challenge revolves around **encoding bases**, specifically **Base64**.  
Your task is to decode the string to unveil the hidden flag.

---

## 📜 **Challenge Description**

The challenge tests your understanding of encoding schemes and how to work with them effectively.  
By leveraging **cryptography tools** or custom scripts, you will decode the given string and solve the puzzle.  

---

## 🛠️ **Solution Steps**

### 1️⃣ **Clone the ENC Tool**  
To solve the challenge, we recommend using the **ENC tool**, a custom Python script for encoding and decoding operations.  

```bash
git clone https://github.com/huynhtrungcip/ENC_tool.git
```

### 2️⃣ Run the ENC Tool
Navigate to the tool's directory and run it:

```bash
cd ENC_tool
python3 ENC_tool.py
```

### 3️⃣ Choose the Base64 Option
From the tool's menu, select Option 1 to access Base64 Encode/Decode functionality:

```diff
+--------+-------------------------------+
| Option |          Description          |
+--------+-------------------------------+
|   1    |      Base64 Encode/Decode     |
+--------+-------------------------------+
```

### 4️⃣ Input the Encoded String
Enter the provided string when prompted:

```bash
Enter the text: bDNhcm5fdGgzX3IwcDM1
```

### 5️⃣ Decode the String
When asked whether to encode or decode, choose the decode (d) option:

```bash
Do you want to encode or decode? (e/d): d
```

### 6️⃣ Retrieve the Flag
The tool will output the decoded text:

```bash
Result: l3arn_th3_r0p35
```
**Congratulations! You’ve successfully decoded the flag.**

### 🏆 Flag
```bash
picoCTF{l3arn_th3_r0p35}
```
### 💡 Key Takeaways
This challenge highlights the significance of mastering basic encoding schemes like Base64.
With tools like ENC, encoding and decoding become efficient and straightforward.

### 🔗 References
**picoCTF Challenge: Official Website**
**Author: Trung Huynh**

### 🎉 Happy Hacking! 🔐
