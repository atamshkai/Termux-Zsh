# Termux-Zsh

If you want to use zsh like original termux,this is for you.

# Installation

pkg up -y && pkg i -y zsh wget

wget https://github.com/atamshkai/Termux-Zsh/raw/main/zsh.tar.xz

tar -xvJf zsh.tar.xz && mv zsh/.* ~/ && rm -rf zsh

chsh -s zsh

exit
