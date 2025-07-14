
---
# 🔐 **stego-xor-rgb-encoder**

> A simple and educational steganography tool for hiding encrypted text inside RGB images using XOR encryption and ASCII encoding.

<p align="center">
  <img src="https://raw.githubusercontent.com/arshc0der/stego-xor-rgb-encoder/refs/heads/main/assets/SXRE.png" alt="Project Cover" width="100%"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-Beta-yellow.svg" alt="Status Badge"/>
  <img src="https://img.shields.io/github/license/arshc0der/stego-xor-rgb-encoder?color=green" alt="License Badge"/>
  <img src="https://img.shields.io/badge/platform-Python-%233776AB.svg" alt="Platform Badge"/>
  <img src="https://img.shields.io/badge/encryption-XOR-%2370D0A5.svg" alt="Encryption Badge"/>
  <img src="https://img.shields.io/badge/tech-OpenCV-%23F37626.svg" alt="OpenCV Badge"/>
  <img src="https://img.shields.io/badge/tech-NumPy-%23013243.svg" alt="NumPy Badge"/>
  <img src="https://img.shields.io/badge/tech-Matplotlib-%23E91E63.svg" alt="Matplotlib Badge"/>
  <img src="https://img.shields.io/github/stars/arshc0der/stego-xor-rgb-encoder?style=social" alt="Stars Badge"/>
  <img src="https://img.shields.io/github/forks/arshc0der/stego-xor-rgb-encoder?style=social" alt="Forks Badge"/>
</p>

[![Last Commit](https://img.shields.io/github/last-commit/arshc0der/stego-xor-rgb-encoder)](https://github.com/arshc0der/stego-xor-rgb-encoder/commits/main)


---

## 📌 Overview

`stego-xor-rgb-encoder` allows you to:

1. **Encrypt** a secret text using XOR cipher with a user-provided key.
2. **Embed** the encrypted text into the pixel values of an RGB image.
3. **Extract** and **Decrypt** the hidden message using the same key.

This combines encryption and steganography in a lightweight, easy-to-understand way.

---

## ✨ Features

- 🔐 XOR encryption with a customizable key  
- 🎨 Embedding encrypted data into RGB pixels  
- 🧩 Compatible with JPG, PNG, and similar formats  
- 📘 Fully documented Jupyter Notebook for educational use

---

## 🛠 Tech Stack

- Python 3.8+  
- OpenCV (`cv2`) for image operations  
- NumPy  
- Matplotlib for visual output

---

## 📂 Repository Structure

```bash
stego-xor-rgb-encoder/
├── stego-xor-rgb-encoder.ipynb     # Fully commented notebook
├── encrypted_output.jpg            # Sample result image (for quick access)
├── README.md                       # Project documentation (you're here)
├── LICENSE                         # MIT License
├── assets/                         # Visual assets for demo
│   ├── original.jpg                # Original unmodified image
│   ├── encrypted_output.jpg        # Encrypted image with hidden text
````

---

## 🚀 Quick Start

### 📥 Clone this repo:

```bash
git clone https://github.com/arshc0der/stego-xor-rgb-encoder.git
cd stego-xor-rgb-encoder
```

### ⚙️ Run the Notebook:

Open `StegnoRGBImplementation.ipynb` in Jupyter and follow the step-by-step instructions.

---

## 💡 Usage Example

```python
secret_text = "hello"
encryption_key = "key123"
```

* Encrypt and embed each character via XOR using the key.
* Embedded values are hidden inside pixel channels.
* Extract and decrypt using the same key.

---

## 🖼️ Demo

| Original Image | Encrypted Image |
|----------------|-----------------|
| ![Original](assets/original.png) | ![Encrypted](assets/encrypted_output.png) |

---

## ⚠️ Disclaimer

> This project is **for educational purposes only** and is **not** intended for secure communications.
> It lacks cryptographic rigor and should NOT be used in production.
> For real encryption, use proven algorithms (AES, RSA) via libraries like [`cryptography`](https://cryptography.io/) or [`PyCryptoDome`](https://www.pycryptodome.org/).

---

## 📜 License

Licensed under the **MIT License**. See `LICENSE` for details.

---

## 🙌 Contributing

Contributions, bug reports, and enhancements are welcome! Please fork the repo and create a pull request.

---

## 🎓 Author

**arshc0der**
📚 Exploring steganography & lightweight encryption methods

---
