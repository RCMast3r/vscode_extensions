getting current vscode extensions for sharing:

`code --list-extensions | sed -e 's/^/code --install-extension /' > my_vscode_extensions.sh`

`cp -f keybindings.json ~/.config/Code/User/`

