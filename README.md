# APT Repository for Vanish CLI

## Quick Install

```bash
# Add the repository
curl -fsSL https://alfredgpennyworth.github.io/apt-repo/key.gpg | sudo gpg --dearmor -o /usr/share/keyrings/vanish.gpg
echo "deb [signed-by=/usr/share/keyrings/vanish.gpg] https://alfredgpennyworth.github.io/apt-repo stable main" | sudo tee /etc/apt/sources.list.d/vanish.list

# Install
sudo apt update
sudo apt install vanish
```

## What is Vanish?

Zero-knowledge self-destructing links. E2E encrypted with AES-256-GCM.

- Website: https://vanish.link
- Source: https://github.com/alfredgpennyworth/vanish-link
