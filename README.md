 Ansible Thinkpad Setup
==========================
My Ansible Setup for my Lenovo Thinkpad.

 What is this playbook good for:
--------------------------------
 + Install common usefull base packages
 + Create dotfiles like .bashrc and .vimrc
 + Setup and configure I3WM as Window Manager

 Install instructions:
-----------------------
```bash
# Clone Git
git clone https://github.com/DO1JLR/ansible_videoschnitt-pc.git
cd ansible_videoschnitt-pc

# Download needed submodules
git submodule update --init --recursive
```

 Video Mixing Software
-----------------------

[DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve/#) is currently not installed automatically because it is not free software.

You need to install it manually!

