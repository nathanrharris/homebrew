# homebrew
This repo is for storing the Homebrew config I use on all of my computers.

Install Homebrew: 

```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"```

Check out repository into /\<home\>/Homebrew:

```git clone git@github.com:nathanrharris/homebrew.git Homebrew```

Link global Brewfile:

```ln -s ~/Homebrew/Brewfile ~/.Brewfile```

Add Packages:

```brew install <package>```

```brew bundle dump -f```

Install Packages from Brewfile

``` brew bundle```
