# Dotfiles for Mac OS

Requirements

- Install prezto & zsh as shell (https://github.com/sorin-ionescu/prezto)
- Shell theme powerlevel9k (https://github.com/bhilburn/powerlevel9k)
- Fonts powerline (https://github.com/powerline/fonts)

---

## Installation

Brew packages missing

- strimio
- logitech-camera-settings

```
git clone https://github.com/Busi87/dotfiles.git ~/dotfiles
cd ~/dotfiles
./setup.sh
```

---

## NVM

```
nvm install node
nvm use system
```

---

## Jenv

```
jenv add $(/usr/libexec/java_home)
jenv global 14.0.1
```

---

## LM-Build

```
cd ~/.GIS-lm-build
rm -rf local
bin/lm install
```
