# vscode-neovim
Keybindings and settings for my VSCode Neovim config. I didn't write these config files and I have no clue what half of the lines in the scripts do, I just know it generally works.

Based on chris@machine's youtube video and his config files I managed to find burried deep in one of his repos. I've made a few slight modifications to match my own preferences.

### Instructions
(It's been a while since I set this up, so it might take a little more configuring than what I'm explaining here)

This is currently working on my Manjaro Linux install, with VSCode installed from snap, and neovim installed from pacman.

After everything is installed and these files are downloaded, place them in the corresponding locations (or paste the contents into the files that are already there)

````
~/.config/Code/User/keybings.json
~/.config/Code/User/settings.json
~/.config/nvim/init.vim
~/.config/nvim/vscode/settings.vim
````
I made a few minor cosmetic/control changes like adding the horizontal scroll bar back, and setting `ctrl+e` back to scrolling the window down with the cursor in place like neovim normally has. I don't remember what it was changed to. Feel free to dig into any of the files to tweak things the way you like them.
