# Neovim Prutssessie

### Setup Instructie

#### Packages
Installeer het volgende:
- ansible

```bash
sudo apt install ansible
```

#### Setup instructie
Zorg ervoor dat jouw user sudo permissies heeft zonder het in te hoefen voeren van een wachtwoord:
```bash
echo 'neovim ALL=(ALL) NOPASSWD: ALL' | sudo tee /etc/sudoers.d/neovim
```
