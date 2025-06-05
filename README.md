# alg-tunnel

Expose your local server to the internet using a static subdomain over a secure FRP-based tunnel.

---

## ✨ Features

- Simple CLI: `tunnel <subdomain> <port>`
- Static subdomain: `dev1.tunnel.algomative.com`
- Secure communication with token-authenticated FRP server
- Supports both `amd64` and `arm64` Linux systems
- Lightweight & offline-capable after install

---

## 🛠️ Installation (Ubuntu / Debian)

Run this once to add the APT repo:

```bash
echo "deb [trusted=yes] https://algomative.github.io/alg-tunnel-apt/apt stable main" | sudo tee /etc/apt/sources.list.d/alg-tunnel.list
sudo apt update
sudo apt install alg-tunnel
```

