# PXLCrypt

**PXLCrypt** is a lightweight, browser-based **image steganography tool** that lets you hide secret messages inside images using a password.  
Fully client-side, no server required, with a stylish **Cyberpunk Neon** interface.

Try it Online: https://programmingexperiencelab.github.io/PXLCrypt/


---

## 🚀 Features

- **Hide Messages in Images**: Encode & Decode secret messages in PNG images.  
- **Password Protection**: Messages can only be revealed with the correct password.  
- **Client-Side Only**: No data leaves your device.  
- **Retro-Neon UI**: Animated Matrix-style background with glitch effects.  
- **Lightweight & Fast**: Built with Vanilla JS, no external libraries.  

---

## 🛠 How to Use

1. Open `index.html` in your browser.  
2. **To Encode a Message**:  
   - Upload a PNG image.  
   - Enter your secret message.  
   - Enter a password.  
   - Click **Encode & Download**.  
3. **To Decode a Message**:  
   - Upload the encoded image.  
   - Enter the password.  
   - Click **Decode Message**.  
   - Your hidden message will appear in the output box.  

---

## ⚠️ Limitations

- Current encryption is **XOR-based** — lightweight and fun, but not cryptographically strong.  
- Maximum message length: 1000 characters (to avoid overflowing the image).  
- Only supports PNG images.  

---

## 🔮 Future Enhancements

- Upgrade to **AES-256** for stronger encryption.  
- Drag-and-drop support for images.  
- QR code export for decoded messages.  
- Full UTF-8 character support.  
- Progressive Web App (PWA) version.  
- Support for larger files via chunking.  

---
## 📜 License

© 2025 **PXL – Programming eXperience Lab**. All rights reserved.  

- **Allowed:** Personal use and experimentation on your own device.  
- **Not Allowed:** Developing, modifying, rewriting, or selling this software in any form.  

---

Made with ❤️ by **PXL – Programming eXperience Lab**  
Cyberpunk Neon UI + Vanilla JS Magic ✨
