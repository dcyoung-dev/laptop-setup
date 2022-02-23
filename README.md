# Laptop Setup 

## Getting Started
```shell
curl --remote-name https://raw.githubusercontent.com/dcyoung-dev/laptop-setup/main/setup
```

## What does it do?
- Copies the `laptop_local` file to `~/.laptop.local`
- Runs `mac` script from [https://github.com/dcyoung-dev/laptop]
- `laptop_local` is automatically run after `mac` script
- `laptop_local` pulls in dotfiles from [https://github.com/thoughtbot/dotfiles]
- `laptop_local` pulls in dotfiles from [https://github.com/dcyoung-dev/dotfiles-local]
- `laptop_local` installs all dotfiles using `rcup`
- Runs `macos` script from [https://github.com/dcyoung-dev/mac-setup/blob/master/config/macos.sh]


### TODO
- [x] `curl` laptop_local repo to `--output ~/.laptop.local`
  - [x] includes call to `rcup`
  - [x] includes Brewfile
  - [x] adds foreman gem
  - [x] Add dotfiles
- [x] run `mac.sh` from laptop repo
