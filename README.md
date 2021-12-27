# @soramitsukhmer/setup

An automated platform setup and provisioning scripts for @soramitsukhmer.

> Requested by @phuylai-oeung and @phyrumsk

## Supported platforms

- [x] macOS
- [ ] Linux
- [ ] Windows 10/11

### Install & Update Script

```sh
curl -o- https://raw.githubusercontent.com/soramitsukhmer/setup/main/install | sh
```

#### Environments

**Dry run**:

To test drive the installer set `SETUP_DRY_RUN=1`

```sh
curl -o- <url-to-installer> | SETUP_DRY_RUN=1 sh
```

**Verbose mode**:

Set the `CI=1` to run in verbose mode.


```sh
curl -o- <url-to-installer> | CI=1 sh
```

## What this does?

Just-in-case someone doesn't know what this does. This will install the following formula/cask via Homebrew.


#### Supported platforms

- [x] macOS
- [ ] Linux
- [ ] Windows 10/11

### Formula

**commons**

- `antigen` - The plugin manager for zsh
- `svn` - It just `svn`
- `whalebrew` - Homebrew, but with Docker images

**developments**

- `git` - It just `git`
- `gh` - GitHub in your terminal
- `node@14` - Node.js v14
- `yarn` - Yarn is a package manager
- `deno` - A modern runtime for JavaScript and TypeScript

**fonts**

- `khmer-unicode-layout`
- `font-fira-code`
- `font-khmeros-bundle`
- `font-open-khmer-school`
- `font-kantumruy`
- `font-kdam-thmor`

**stack**

- `awscli`
- `vagrant`

**utilities**

- `mas` - Mac App Store command line interface
- `certstrap` - Tools to bootstrap CAs, certificate requests, and signed certificates.
- `tldr`
- `htop`
- `bat` - "cat" on steroids
- `exa` - A modern replacement for ls
- `prettyping`
- `lolcat`
- `tree` - List directories in a tree structure
- `httpie`
- `thefuck` - No f*ck given
- `jq` - lightweight and flexible command-line JSON processor
- `watch` - Execute a program periodically, showing output fullscreen

### Cask

Homebrew Cask only supported on macOS. Sorry linux users!

This will installs:

- `google-chrome` - Google Chrome
- `firefox` - Firefox
- `visual-studio-code` - Code editing. Redefined.
- `fork` - Fast and friendly git client
- `iterm2` - iTerm2 is a replacement for Terminal
- `tableplus` - TablePlus
- `docker` - Docker
- `insomnia` - Insomnia
- `virtualbox` - Oracle VirtualBox
- `gpg-suite` - GPG Suite
- `google-drive` - Google Drive
- `chrome-remote-desktop-host` - Chrome Remote Desktop Host
- `mounty` - NTFS Helper
- `cheatsheet` - Know your short cuts


## References

- https://github.com/socheatsok78/setup-macos
