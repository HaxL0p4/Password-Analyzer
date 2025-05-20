<p align="center">
  <img src="https://github.com/HaxL0p4/Password-Analyzer/blob/main/img/pass.png" alt="Password Analyzer" width="300" />
</p>

<h1 align="center">Password Analyzer</h1>

<p align="center">
  A client-side web tool that evaluates password strength by estimating entropy, brute-force time, and generating SHA-256 hashes.  
  Includes a hacker-style terminal for advanced commands and checks against known password leaks, ensuring privacy and real-time security insights.
</p>

---

## Features

- Real-time password strength assessment (entropy, strength level)
- Estimated brute-force cracking time
- SHA-256 hashing on client side
- Leak detection via Have I Been Pwned API
- Interactive hacker-style terminal with useful commands
- Privacy-first: no password data leaves the client

---

## Usage

1. Open `index.html` in your browser.
2. Enter your password in the input field to see its analysis.
3. Use the terminal below to run commands like `help`, `entropy`, `hash`, `leak`, `breachcount`, `suggest`, and `clear`.

---

## Commands in Terminal

| Command     | Description                                |
|-------------|--------------------------------------------|
| `help`      | Show available commands                     |
| `entropy`   | Show entropy of the entered password       |
| `hash`      | Display SHA-256 hash of the password       |
| `leak`      | Check if password is found in data breaches|
| `breachcount`| Show how many times password appeared in leaks |
| `suggest`   | Generate a secure random password           |
| `clear`     | Clear the terminal output                    |

---

## Technologies

- HTML5, CSS3, JavaScript (ES6+)
- Web Crypto API for secure hashing
- Fetch API for checking leaked passwords

---

## License

MIT License

---

<p align="center">
  by L0PA — <a href="https://github.com/HaxL0p4" target="_blank" rel="noopener noreferrer">GitHub</a>
</p>
