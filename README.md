# dotfiles
For bootstrapping development machines

Inspired by
https://github.com/kespinola/dotfiles



TODOS:
- Install poetry

- Vscode must run zsh as login shell. Us this:
'''

{
    "terminal.integrated.profiles.linux": {
      "zsh (login)": {
        "path": "zsh",
        "args": ["-l"]
      }
    },
    "terminal.integrated.defaultProfile.linux": "zsh (login)",
    "terminal.integrated.fontFamily": "MesloLGS NF"
}

'''