# Configuration for dircolors on WSL2 and Windows Terminal

The default color of WSL2 and Windows Terminal doesn't look good inside Windows folders. This configuration helps remove the highlight colors to make it look prettier. 

## Usage:
```
cd
git clone git@github.com:cuiwc/wsl-dir-colors.git .wsl-dir-colors
ln -sf .wsl-dir-colors/dircolors .dircolors

# If using zsh. Change to .bashrc if bash is used.
cat >>.zshrc <<EOF
# Setup dircolors
eval `dircolors ~/.dircolors`
EOF
```
