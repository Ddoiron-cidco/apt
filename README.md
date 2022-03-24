## Usage

```bash
sudo curl https://radxa-repo.github.io/apt/pubkey.gpg -o /usr/share/keyrings/Radxa-archive-keyring
sudo gpg --dearmor /usr/share/keyrings/Radxa-archive-keyring
# Debian
sudo tee /etc/apt/sources.list.d/radxa.list <<< "deb [signed-by=/usr/share/keyrings/Radxa-archive-keyring.gpg] https://radxa-repo.github.io/apt/ bullseye main"
sudo apt update
```

