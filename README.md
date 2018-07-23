# DotFiles
DotFiles Setup Preferences for common environments (Esp. for Web Artisans).

# Info

## .zshrc
### Instructions
Ensure you have [ZSH](https://gist.github.com/derhuerst/12a1558a4b408b3b2b6e) installed and also [Oh-My-ZSH](https://github.com/robbyrussell/oh-my-zsh) for that *etxra sauce*.
Copy **.zshrc** file to our home folder
As for this specific file, [bhilburn/powerlevel9k](https://github.com/bhilburn/powerlevel9k) theme has been used. Integrates well vith [vscode](https://code.visualstudio.com). More styling can be found [here](https://github.com/bhilburn/powerlevel9k/wiki/Stylizing-Your-Prompt)
 Sample terminal output has been attached here.
![alt text](http://url/to/img.png)


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