# Termux-Zsh

![](https://raw.githubusercontent.com/atamshkai/Termux-Zsh/main/Screenshot_2023-06-22-01-02-48-340_com.termux.jpg)

If you want to use zsh like original termux,this is for you.

# Installation

```

pkg up -y && pkg i -y zsh wget

wget https://github.com/atamshkai/Termux-Zsh/raw/main/zsh.tar.xz

tar -xvJf zsh.tar.xz && mv zsh/.* ~/ && rm -rf zsh

chsh -s zsh

exit

```

# For Debian Linux

```

apt update -y && apt install -y zsh wget

wget https://github.com/atamshkai/Termux-Zsh/raw/main/zsh.tar.xz

tar -xvJf zsh.tar.xz && mv zsh/.* ~/ && rm -rf zsh

chsh -s /bin/zsh

exit

```

# For Archlinux

```

pacman -Syu --noconfirm && pacman -S zsh wget --noconfirm

wget https://github.com/atamshkai/Termux-Zsh/raw/main/zsh.tar.xz

tar -xvJf zsh.tar.xz && mv zsh/.* ~/ && rm -rf zsh

chsh -s /bin/zsh

exit

```

# For Alpine Linux

```
apk add zsh wget && echo "exec zsh" >>~/.bash_profile

wget https://github.com/atamshkai/Termux-Zsh/raw/main/zsh.tar.xz

tar -xvJf zsh.tar.xz && mv zsh/.* ~/ && 
rm -rf zsh

exit

```

# For Fedora

```
dnf install zsh wget 

wget https://github.com/atamshkai/Termux-Zsh/raw/main/zsh.tar.xz

tar -xvJf zsh.tar.xz && mv zsh/.* ~/ && rm -rf zsh

chsh -s /bin/zsh

exit
```
