# 🕵️‍♂️ Steganography using LSB in Images

A Python-based project to hide and retrieve secret messages inside PNG images using the Least Significant Bit (LSB) technique — an invisible and secure form of communication.

---

## 📌 Table of Contents

- [🔍 Problem Statement](#-problem-statement)
- [🧠 How It Works](#-how-it-works)
- [🛠️ Technologies Used](#-technologies-used)
- [⚙️ Setup & Installation](#-setup--installation)
- [🚀 Usage Instructions](#-usage-instructions)
- [🖼️ Sample Outputs](#-sample-outputs)
- [📈 Results](#-results)
- [💡 Future Scope](#-future-scope)
- [📚 References](#-references)

---

## 🔍 Problem Statement

In the digital world, data privacy is becoming increasingly important. While encryption protects the content, it can still draw attention. Steganography offers a stealthy alternative by hiding sensitive information inside normal-looking files like images.

This project focuses on implementing an image-based steganography system that uses **Least Significant Bit (LSB) manipulation** to embed secret text inside a PNG image. The hidden message does not cause visible distortion in the image, making it ideal for confidential, undetectable communication.

---

## 🧠 How It Works

1. **Text to Binary**: Converts a text message into a binary stream.
2. **Embedding**: Hides the binary stream inside the LSBs of pixel color values (usually the red channel).
3. **Header**: Encodes message length as a header to ensure accurate decoding.
4. **Decoding**: Extracts LSBs from the image, reconstructs the binary, and converts it back to the original text.
5. (Optional) A **checksum** can be added for message validation.

---

## 🛠️ Technologies Used

### Programming Language
- Python 3.8+

### Libraries & Frameworks
- `Pillow` – Image manipulation
- `numpy` – Array operations
- `hashlib` – For optional checksum generation
- `matplotlib` – (Optional) For visual comparison

### Tools
- Jupyter Notebook (for demonstration)
- VSCode / Any IDE

---
## 💡 Future Scope

- 🛡️ Add encryption (e.g., AES) before embedding for extra security.
- 🖼️ Support more formats like JPEG (lossy) using advanced methods.
- 🧠 Integrate anti-steganalysis techniques to avoid detection by AI.
- 🖥️ Build a full GUI desktop app using Tkinter or PyQt.
- ☁️ Enable cloud-based image sharing with hidden payloads.

---

## 📚 References

- Gonzalez & Woods, _Digital Image Processing_
- [Wikipedia – Steganography](https://en.wikipedia.org/wiki/Steganography)
- [Pillow Documentation](https://pillow.readthedocs.io/)
- [NumPy Documentation](https://numpy.org/doc/)
- Research Paper: _A Survey of Image Steganography Techniques – IJCSES_

---

## 🧑‍💻 Author

**Avi Seth**  
Student at Amity University Noida  
GitHub: [github.com/AviSeth20](https://github.com/AviSeth20)
