# Homebrew
Install [Homebrew](https://brew.sh)

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

# Reinstall Homebrew  stuff
## Create Brewfile on old Mac
1. `brew bundle dump`

	_creates Brewfile in the current directory from currently-installed packages_

2. edit Brewfile and remove unnecessary stuff
## install everything from the Brewfile

```bash
brew bundle install
```
