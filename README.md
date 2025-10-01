# Brute-Force Attack Simulator 🎯

This project is a simple, static website designed for educational purposes. It serves as a safe and legal target for students learning about cybersecurity and how brute-force attacks work. The goal is to demonstrate the principles of automation, password hashing, and basic security measures like rate limiting in a hands-on way.

## 🚀 Live Demo

You can see the live challenge page here:
**[https://gentritks.github.io/brute-force-simulator/](https://gentritks.github.io/brute-force-simulator/)**



---

## 🎯 The Challenge

Your mission is to write a script (e.g., using **Python with Selenium**) that can automatically interact with the live demo page to discover the correct 4-digit PIN.

Your script must be able to:
1.  Open the webpage in a browser.
2.  Iterate through all possible 4-digit PINs (`0000` to `9999`).
3.  Enter each PIN into the input box and click the "EXECUTE" button.
4.  Detect when the correct PIN is found by checking for the redirect to `success.html`.

---

## ✨ Features

This simulation includes several features to make the challenge more realistic and educational:

* **Realistic Interface:** A dark, terminal-style theme to make the challenge more engaging.
* **Client-Side Hashing:** The password check uses SHA-256 hashing, preventing the PIN from being visible in the source code in plain text.
* **Dynamic Hash Assembly:** The correct hash is built by JavaScript *after* the page loads, making it resistant to simple web scraping tools that don't render JavaScript.
* **Rate Limiting:** A small delay is implemented on failed attempts, demonstrating a basic defense mechanism against brute-force attacks.

---

## 🔧 How to Use for Your Own Class

Want to use this for your own classroom or event? It's easy!

1.  **Fork this Repository:** Click the "Fork" button in the top-right corner to create your own copy.
2.  **Enable GitHub Pages:** In your new forked repository, go to `Settings` > `Pages`. Under "Branch," select `main` and click `Save`.
3.  **Share Your Link:** You'll get your own live URL to share with your students! You can even go into the `index.html` file and change the password hash to a different PIN if you wish.

---

## ⚠️ Ethical Disclaimer

This project is created for **educational purposes only**. The techniques and scripts developed to solve this challenge should **NEVER** be used on any website or system without explicit, written permission from the owner. Unauthorized access to computer systems is illegal.
