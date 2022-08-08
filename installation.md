# Installing VI

VI (or VIM, AKA VI improved) is the text editor that works right out of your terminal. It's the best way to edit and run code simply and in a lightweight fashion. Here's how to install:

## MacOS

VI, by default, comes with MacOS. If you want to add the application (MacVIM), which supports syntax highlighting and is lightweight, run the followingL

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
export PATH=/usr/local/bin:$PATH
brew update
brew install vim && brew install macvim
brew link macvim
```

## Linux/BSD

VIM should come with several different distros, but if it does not, consult your distributor regarding this.

## Windows

If you can, don't use Windows. If you *have to*, download it from [here][vim-download-windows].

[vim-download-windows]: https://www.vim.org/download.php#pc
