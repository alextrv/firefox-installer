# firefox-installer
Install and Update Firefox for GNU/Linux from Mozilla official website using only one command in terminal

## Installation
To install firefox-installer type in terminal:

    sudo wget https://raw.githubusercontent.com/alextrv/firefox-installer/master/firefox-installer -O /usr/bin/firefox-installer # OR /usr/local/bin/firefox-installer
    sudo chmod +x /usr/bin/firefox-installer # OR /usr/local/bin/firefox-installer
    firefox-installer -i   # Install Firefox

Or clone this repo:

    cd /path/to/dir/
    git clone https://github.com/alextrv/firefox-installer.git
    cd firefox-installer
    chmod +x firefox-installer
    ./firefox-installer -i   # Install Firefox

## Options:
    Only one option can be used at the same time.

    -i, --install     Install or update (if installed) Firefox from official website
    -u, --uninstall   Uninstall Firefox
    -s, --status      Show installed and upstream Firefox versions
