# INSTALLER
heavily inspirder by [icicle](https://github.com/snowfallorg/icicle) installer of SnowflakeOS

### explanations:
- [x] Enabled by default
- [ ] Disabled by default

# Sections
- A first time install (dropdown explanation)
- B install from existing machine in dotfiles repo flake (dropdown explanation )
- C Advanced installation (dropdown explanation) (accessible later in installation)


# Main screen
- [ ] First time install
- [ ] Install from dotfiles repo



#
# Section A

## 1a. First Install on new machine
- About distro
- distro image
- github link
- github repo to store dotfiles (textbox) (dropdown with explanations)
- [ ] allow internet access (Use latest online sources instead of packaged default flake in iso )
- [ ] allow location (For timezone)

## 2a. language
- search (textbox)
- [x] english
- [ ] other (dropdown menu)
## 3a. keyboard layout
- try layout (textbox)

- [x] english (us)
- [ ] other

## 4a. timezone
- [x] time zone by location [current time in location] [grayed out if location disabled]
- [ ] other

## 5a. Creating a new user

### Normal User options
- name
- username
- password x2
- [ ] autologin
#

### Root user opions opions
- [x] root password x2
- [ ] user password for root

## 6a. Hardware detection (beta)
- [ ] Change hostname? (textbox)
#
- [x] Are you using this device?
- [ ] No - search (textbox)
- [ ] No - Do not use nixos-hardware
#
- image of device
- brand
- model
- public model
- specs

- [nix hardware modules explained](https://github.com/nixos/nixos-hardware) (dropdown with tldr)
- - nix hardware autodetection based on the currently booted system, with a plausible overwrite to a different device or none


## 7a. Desktop enviroment choice
- [x] Vanilla GNOME (version number) [no extensions]
- [ ] Vanilla KDE (version number)

- [ ] Opinionated GNOME (version number)
- (dropdown) gnome with an opinonated experience (to be determined) (eg. default extensions, packages, yada yada..)

- [ ] Opinionated KDE (version number)
- (dropdown) kde with an opinonated experience (to be determined)

- [ ] Advanced installation [ documentation continues in section C ]
- (dropdown) Choose your own DE, modules, advanced configuration

## 8a. Package managment
- [x] flatpak  (enable flathub/beta)
- [x] appimage
#
- [x] Install by default:
- [x] vscode (dropdown for vscodium, OSS)
- [x] chromium (dropdown for google-chrome, ungoogled chromium, forks)
- [ ] firefox (dropdown for forks)
- [ ] discord (dropdown for 3rd party clients)
- [ ] steam
- [ ] ...

## 9a. kernel
 - [x] lts (dropdown with tldr)
 - [ ] latest (dropdown with tldr)
 - [ ] libre (dropdown with tldr)
 - [ ] zen (dropdown with tldr)

## 10a. Disk managment
### Basic
- Format a full disk
- [x] chosen disk
- [ ] non chosen disk


### Advanced
- [x] chosen disk (show device name and size, !disallow smaller than 32gb)
(dropdown)
- format y/n toggle
- disk partitions (button to gparted)
- mount:  /, /home, /boot /nix - necessary (others: /var, /opt)
- mount other drives (partition)- (textbox) (eg. windown partition in dualboot)

- [ ] non chosen disk

## 11a. Summary
- lang
- layout
- timezone
- hardware
- user (name, username, hostname)
#
Packages installed by default list
- Desktop Enviroment (GNOME Opinionated, GNOME, KDE, Custom..)
- if custom, summary of custom
- browser (chrome/firefox/other)
- vscode
- discord
- ...


## 12a. Install screen
- (first prompt the user with a warning and then proceed)
- loading bar
- general nixos and distro info
- console output icon

## Instalation finish
#

# Section B

## Section 1b-6b with defaults not set (same as 1a-6a)

## 1b. Installation from dotfiles flake repo's existing machine
- About distro
- distro image
- github link
- github repo to store dotfiles (textbox) (dropdown with explanations)
- [x] allow internet access [Forced enabled/Grayed out for online repo]
- [ ] allow location

## 2b. Tweak or continue
- Use the configuration in dotfiles (skips sections b7-b9, b3-b6 then b10-b12)
- Edit and create new configuration in dotifles ()

## 3b. language

## 4b. key layout

## 5b. timezone

## 6b. Creating a new user

## Section 7b-10b with defaults used from dotfiles machine chosen

## 7b. Desktop enviroment choice
- ...
- [ ] Advanced installation [ documentation continues in section C ]
- (dropdown) Choose your own DE, modules, advanced configuration
- ...

## 8b. Package managment

## 9b. kernel

## 10b. Disk managment
- Show the dotfiles layout
- [x] to proceed, force to read, error on non-compatible disk

## 11b. Summary

## 12b. Install screen

## Instalation finish
#

# Section C

## 1c. Advanced installation

- DE, Internet browser choice, gnome extensions,
- developer mode - see developer_mode.md
- modules - todo
- ...

## 2c, Return to section 8a or 8b
