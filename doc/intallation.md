# INSTALLER
## explanations:
- [x] Enabled by default
- [ ] Disabled by default
- option
- option (text box)

# Main choice
- 1a. first time install (dropdown explanation)
- 1b. install from existing dotfiles flake (dropdown explanation )
-

## 1a. First Install on new machine
- About distro
- distro image
- github link
- github repo to store dotfiles (textbox) (dropdown with explanations)
- [ ] allow location
- [ ] allow internet access

## 2a. language
- [x] english
- [ ] other
## 3a. key layout
- try layout (textbox)

- [x] english (us)
- [ ] other

## 4a. timezone
- [x] time zone by location [current time in location]
- [ ] other


## 5a. Hardware detection (beta)
- [ ] Change hostname? (textbox)
#
- [x] Are you using this device?
- [ ] No - search (textbox)
#
- image of device
- brand
- model
- public model
- specs

- [nix hardware modules explained](https://github.com/nixos/nixos-hardware)

## 6a. Creating a new user
### Normal User options
- name
- username
- password x2
- [x] autologin
#
### Root user opions opions
- [x] root password x2
- [ ] user password for root


## 7a. Desktop enviroment choice
- [x] GNOME (version number)
- [ ] Vanilla GNOME (version number) [no extensions]
- [ ] KDE (version number)

## 8a. Package managment
- [x] flatpak  (enable flathub/beta)
- [x] appimage
#
- [x] Install by default:
- [x] vscode (dropdown for vscodium, OSS)
- [x] chromium (dropdown for google-chrome, ungoogled chromium)
- [ ] firefox (dropdown for forks)
- [ ] discord (dropdown for 3rd party clients)
- [ ] steam

...

## 9a. kernel
 - [x] lts
 - [ ] latest
 - [ ] libre
 - [ ] zen

## 10a. Disk managment

- Basic
- - Format a full disk
- [x] chosen disk
- [ ] non chosen disk


- - Advanced
[x] chosen disk (show device name and size, !disallow smaller than 32gb)
- - - disk partitions
- - - format y/n
- - - mount:  /, /home, /boot /nix - necessary (others: /var, /opt)


## 11a. Summary
- lang
- layout
- timezone
- hardware
- user (name, username, hostname)
#
Packages installed by default list
- Desktop Enviroment (GNOME, KDE, other)
- browser (chrome/firefox)
- vscode
- discord
-


## 12.a Install screen
- loading bar
- general nixos and distro info
- console output icon

