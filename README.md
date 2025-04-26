# 📦 Reviver

**Dead-simple CLI to backup and restore your dotfiles with encryption and GitHub Gist — no servers, no headaches.**

---

## 🚀 What is Reviver?

Reviver is a zero-setup tool that lets you **securely back up and restore** your important dotfiles (`.bashrc`, `.vimrc`, `.zshrc`, etc.).  
Your backups are **encrypted** and **stored safely** in your **private GitHub Gists** — no need to set up servers, SSH configs, or complicated Git workflows.

Just **save**, **restore**, and **relax**.

---

## ✨ Features

- 🔒 **End-to-End Encryption** — Your dotfiles are encrypted before leaving your machine.
- ☁️ **Private GitHub Gist Storage** — Simple, free, and secure.
- 🧹 **Zero Configuration** — Just curl the installer and start backing up.
- ⚡ **One Command Backup & Restore** — No learning curve, just magic.
- 🔥 **No Git, No Symlinks, No SSH Needed** — Unlike heavy alternatives.

---

## 🛠️ How It Works

### Backup your dotfiles

```bash
reviver save ~/.bashrc ~/.vimrc ~/.zshrc
```

- Compresses your dotfiles into a single archive.
- Encrypts the archive using OpenSSL or age.
- Uploads the encrypted backup to your **private GitHub Gist**.

---

### Restore your dotfiles

```bash
reviver load
```

- Downloads the encrypted archive from your Gist.
- Decrypts it (asks for your password or SSH key).
- Extracts your files back into your home directory.

---

## 🪰 Requirements

- **Bash** (or any POSIX-compatible shell)
- **GitHub CLI** (`gh`) — [Install here](https://cli.github.com/)
- **OpenSSL** or **age** for encryption

---

## ⚡ Installation

```bash
curl -sL https://yourdomain.com/install.sh | bash
```

(Replace `yourdomain.com` with your actual link later)

---

## 📋 Why Reviver?

| Feature | Reviver | Other Tools |
|:--|:--|:--|
| Encryption | ✅ | ❌ |
| GitHub Gist Storage | ✅ | ❌ |
| Zero Setup | ✅ | ❌ |
| Works Without Git Config | ✅ | ❌ |
| One Command Usage | ✅ | ❌ |

---

## 🧐 Roadmap

- [ ] GUI Version (future)
- [ ] Cloud Provider Backup Option (AWS S3, Dropbox)
- [ ] Scheduled Backups (via Cron jobs)
- [ ] Passwordless Mode (using SSH Keys only)

---

## 🤝 Contributing

Pull Requests are welcome!  
Feel free to open issues or suggest new features.

---

## ⚖️ License

MIT License.

---

# 🎯 Quick Philosophy

**Dotfile backups should not be harder than sending an email. Reviver makes it a one-liner.**

---

# 💬 Final Word

If you use Reviver and like it, share it with your friends!  
Built for lazy hackers, busy developers, and everyone in between.

