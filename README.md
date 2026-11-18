# 🔐 Cipher Text

![C](https://img.shields.io/badge/Language-C-00599C?style=flat-square&logo=c&logoColor=white)
![Type](https://img.shields.io/badge/Type-CLI-lightgrey?style=flat-square)

A simple **Caesar cipher** tool written in C. Give it a key and some text, and it encrypts it. Give it the same key and the encrypted text, and you get the original message back.

I wrote this while learning strings and character handling in C. It was a fun way to see how a tiny bit of math (`(index + key) % 26`) can hide a message.

---

## ✨ Features

- 🔒 **Encrypt** plain text with any numeric key
- 🔓 **Decrypt** cipher text with the same key
- 🔠 Keeps upper and lower case as they are
- ✍️ Spaces, numbers and symbols are left untouched
- 🔁 Menu loop, so you can encrypt/decrypt as many times as you want before exiting

## 🚀 Run it

```bash
gcc ciphertext.c -o cipher
./cipher
```

Then pick an option:

```text
For Encrypt Press 1.
For Decrypt Press 2.
For EXIT Press 0.
```

### Example

```text
Enter the KEY: 3
Enter the Plain Text: Hello World
Ciphertext (Encrypted) Text: Khoor Zruog
```

## 🧠 What I practiced

- Working with `char` arrays and `fgets`
- `ctype.h` helpers like `islower` and `isupper`
- Modular arithmetic for wrapping around the alphabet

---

Made by **Abdullah Al Jubayer** · [GitHub](https://github.com/abdullahaljubayer-101) · [Portfolio](https://abdullahaljubayer.com)
