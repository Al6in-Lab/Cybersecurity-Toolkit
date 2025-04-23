README.txt

==============================
 ULTIMATE SECURITY TOOLKIT
==============================

Author: Al6in
File: App.html

DESCRIPTION
-----------
The Ultimate Security Toolkit is a lightweight, browser-based suite of cybersecurity tools built entirely in HTML, CSS, and JavaScript. 
It is designed to be offline-capable and simple to use, while also including a unique, fully custom encryption/decryption engine created from scratch.

This tool is ideal for ethical hackers, developers, privacy enthusiasts, and curious minds looking for a personal security assistant.

FEATURES
--------
🛡️ Custom Encryption / Decryption:
- Original cipher designed and implemented by the developer.
- Modifiable and extensible with your own rules.
- Character-to-token mapping encryption.
- Handles letters, numbers, symbols, and whitespace.
- Reversible (with reverse mapping logic).
- Error-handling included for unmatched sequences.

🔐 Password Strength Checker:
- Real-time feedback.
- Scans for length, uppercase, lowercase, digits, and symbols.
- Visual strength meter and human-readable feedback.

🔢 SHA-256 Hasher:
- One-click hashing of any text input.
- Output can be copied and used for verification, integrity checks, etc.

🧬 Browser Fingerprint Generator:
- Generates basic fingerprint from browser properties.
- Can be used to demonstrate fingerprinting or for educational tracking studies.

🌗 Dark/Light Mode Toggle:
- Built-in theme switcher for eye comfort.

HOW TO USE
----------
1. Open `App.html` in your browser. No installation required.
2. Use the top navigation bar to switch between modules:
   - Home: Overview of tools.
   - Encrypt/Decrypt: Encode or decode your custom messages.
   - Password: Check the strength of your password.
   - Hash: Generate a SHA-256 hash of any text.
   - Fingerprint: See what info your browser reveals.

3. For encryption/decryption:
   - Input your text.
   - Click "Encrypt" to encode using the custom cipher.
   - Click "Decrypt" to decode the text using the reverse mapping.

MODIFYING THE ENCRYPTION SYSTEM
-------------------------------
You can customize or expand the encryption by editing the `rules` object in the script section:
```js
const rules = {
  "a": "1j2",
  "b": "#x9",
  ...
};

