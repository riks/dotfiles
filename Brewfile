# Install command-line tools using Homebrew
# Usage: `brew bundle Brewfile`

tap homebrew/dupes

# Make sure we’re using the latest Homebrew
update

# Upgrade any already-installed formulae
upgrade

# Install GNU core utilities (those that come with OS X are outdated)
# Don’t forget to add `$(brew --prefix coreutils)/libexec/gnubin` to `$PATH`.
install coreutils
# Install some other useful utilities like `sponge`
install moreutils
# Install GNU `find`, `locate`, `updatedb`, and `xargs`, `g`-prefixed
install findutils
# Install GNU `sed`, overwriting the built-in `sed`
install gnu-sed --default-names
# Install Bash 4
# Note: don’t forget to add `/usr/local/bin/bash` to `/etc/shells` before running `chsh`.
install bash
install bash-completion

# Install wget with IRI support
install wget --enable-iri

# Install more recent versions of some OS X tools
install homebrew/dupes/grep
#install homebrew/dupes/screen # currently failing with "autoreconf: failed to run aclocal: Permission denied"

# Install other useful binaries
install ack
install bash-git-prompt
install git
install htop-osx
install imagemagick --with-webp
install nano
install nmap
install rename
install ssh-copy-id
install tree

# Remove outdated versions from the cellar
cleanup
