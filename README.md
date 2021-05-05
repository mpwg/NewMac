# Reinstall Homebrew  stuff
## Create Brewfile on old Mac
1. `brew bundle dump`

	_creates Brewfile in the current directory from currently-installed packages_

2. edit Brewfile and remove unnecessary stuff
## install everything from the Brewfile

```console
brew bundle install
```
