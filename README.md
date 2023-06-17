# os-automatic-install
An automatic installer for GNU/Linux operating systems

## To install Arch Linux

### Preparation

- Prepare a usb key with an Arch Linux installer
- Boot on the usb key
- Ensure you have Internet and the curl program

### The installer

To get the menu:
```bash
bash <( curl --silent [https://github.com/Enoxime/os-automatic-install/raw/main/arch_linux.sh](https://raw.githubusercontent.com/Enoxime/os-automatic-install/main/arch_linux.sh) ) -h
```

To install with the minimum options:
```bash
bash <( curl --silent [https://github.com/Enoxime/os-automatic-install/raw/main/arch_linux.sh](https://raw.githubusercontent.com/Enoxime/os-automatic-install/main/arch_linux.sh) ) -r 'ROOT_PASSWORD_HERE' -u 'YOUR_USERNAME' -p 'YOUR_PASSWORD'
```
