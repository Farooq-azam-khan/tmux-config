# Setup 
```
$ git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
$ wget -O ~/.tmux.conf https://raw.githubusercontent.com/Farooq-azam-khan/tmux-config/main/.tmux.conf 
```
1. lauch tmux
2. source the file with `tmux source ~/.tmux.conf`
3. install plugins with `<leader>I`

# Useful commands to Know
* [cheathseet](https://tmuxcheatsheet.com/)
* `<prefix>b` goes to last window
* `<prefix>q` shows pane number
* `<prefix>z` zoom into pane
* `<prefix>x` close window

## Session Commands
* `<prefix>s` list all session while inside tmux session.
 * Can navigate to enter into an ongoing session or press escape to keep yourself in the current session
* `tmux attach -t [session-name]` attaches to tmux session by name
* `tmux new -s [session-name]` create a new session

  
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

# TODO
* [ ] figure out how to use `tmux-yank`
* [x] is mouse support for tmux needed/good? yes - good for some usecases. could be an anti-pattern if always relying on it. 
