### 1. Install Kanata
```bash
yay -S kanata-bin

2. Clone Repository
Bash

mkdir -p ~/.config/kanata
git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git) ~/.config/kanata

3. Setup and Start Service
Bash

mkdir -p ~/.config/systemd/user/
cp ~/.config/kanata/kanata.service ~/.config/systemd/user/
systemctl --user daemon-reload
systemctl --user enable --now kanata

4. Verify Status
Bash

systemctl --user status kanata
