# neovim_setup

## Requirements
Install neovim >= v0.8

## Windows
```powershell
git clone https://github.com/wbthomason/packer.nvim "$env:LOCALAPPDATA\nvim-data\site\pack\packer\start\packer.nvim"
```

### Copy
```bash
cp ~/.neovim_setup/lua/ -R ~/AppData/Local/nvim
cp ~/.neovim_setup/init.lua ~/AppData/Local/nvim
```

## Unix
TODO

### Copy
```bash

mkdir -p ~/.config/nvim/lua/ && cp plugins.lua $_ /
mkdir -p ~/.config/nvim/ && cp init.vim $_ /

```
