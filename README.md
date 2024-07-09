# Setup 
```
$ git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
$ wget -O ~/.tmux.conf https://raw.githubusercontent.com/Farooq-azam-khan/tmux-config/main/.tmux.conf 
```
1. lauch tmux
2. source the file with `tmux source ~/.tmux.conf`
3. install plugins with `<leader>I`


# Startship
[https://starship.rs/](https://starship.rs/)
https://dev.to/nexxeln/my-developer-workflow-using-wsl-tmux-and-neovim-55f5
1. Install nerdfont with the following: 
```bash
# pick a font: [https://www.nerdfonts.com/font-downloads](https://www.nerdfonts.com/font-downloads)
 mkdir ~/.local/share/fonts
wget -O ~/.local/share/fonts/Agave.zip ~/. https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/Agave.zip
# unzip in fonts dir 
cd ~/.local/share/fonts
unzip Agave.zip

# update cache 
fc-cache -f -v

# cleanup
rm Agave.zip
```

2. Install starship with `curl -sS https://starship.rs/install.sh | sh`
2.1 might have to create/update user password with `sudo passwd [username]` 
