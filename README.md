# DotFiles
DotFiles Setup Preferences for common environments (Esp. for Web Artisans).

# Info
## .aliases
- Common file manipulation/listing
- Git operations
- Laravel artisan commands
- NPM commands/operations

### Instructions
Copy **.alias** file to our home folder and link it to .bashrc and .zshrc.

**.bashrc:**
```bash
if [ -f ~/.aliases ]; then
    . ~/.aliases
fi
```
**.zshrc:**
```bash
source $HOME/.aliases
```

# Credits
- [lexxyungcarter/dotfiles](https://github.com/lexxyungcarter/dotfiles)
- [byrongibson/dotfiles](https://github.com/byrongibson/dotfiles)

# Licence
- MIT