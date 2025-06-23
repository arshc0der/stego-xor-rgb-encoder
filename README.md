
---

# 🔐 stego-xor-rgb-encoder

> A simple and educational steganography tool for hiding encrypted text inside RGB images using XOR encryption and ASCII encoding.

![License](https://img.shields.io/badge/license-MIT-green.svg) ![Python](https://img.shields.io/badge/python-3.8%2B-blue.svg) ![Status](https://img.shields.io/badge/status-educational-lightgrey.svg)

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
├── StegnoRGBImplementation.ipynb   # Fully commented notebook
├── encrypted_output.jpg            # Sample result image
├── README.md                       # Documentation (you're here)
├── LICENSE                         # MIT License
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
📚 Final-year student — exploring steganography & lightweight encryption methods

---
