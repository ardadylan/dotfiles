# Dotfiles

## ⌨️ Kanata (Keyboard)
1. **Install:** `yay -S kanata-bin`
2. **Link Config:** ```bash
   mkdir -p ~/.config/kanata
   ln -s ~/dotfiles/kanata-files/kanata.kbd ~/.config/kanata/kanata.kbd

    Setup Service:
    Bash

    mkdir -p ~/.config/systemd/user/
    cp ~/dotfiles/kanata-files/kanata.service ~/.config/systemd/user/
    systemctl --user daemon-reload
    systemctl --user enable --now kanata

🐚 Shell (Coming Soon)
