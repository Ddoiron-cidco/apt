[View on GitHub](https://github.com/radxa-repo/apt)

## Usage

```bash
curl -LsS https://radxa-repo.github.io/apt/pubkey.gpg | gpg --dearmor | sudo tee /usr/share/keyrings/Radxa-archive-keyring.gpg
# Debian
sudo tee /etc/apt/sources.list.d/radxa.list <<< "deb [signed-by=/usr/share/keyrings/Radxa-archive-keyring.gpg] https://radxa-repo.github.io/apt/ bullseye main"
# Or Ubuntu
sudo tee /etc/apt/sources.list.d/radxa.list <<< "deb [signed-by=/usr/share/keyrings/Radxa-archive-keyring.gpg] https://radxa-repo.github.io/apt/ jammy main"
sudo apt update
```
