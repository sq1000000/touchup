# touchup

A shell script used to update various types of packages at the same time on Debian, Arch, or MacOS. The script also cleans many often forgotten corners of the Linux system, making it useful for troubleshooting.

#### To install on Linux:

$ ```sudo false ; wget https://raw.githubusercontent.com/sq1000000/touchup/main/touchup ; sudo chmod +x touchup ; sudo mv touchup /usr/bin/touchup```

#### To install on MacOS:

$ ```sudo false ; wget https://raw.githubusercontent.com/sq1000000/touchup/main/touchup ; sudo chmod +x touchup ; sudo mv touchup /opt/homebrew/bin/touchup```

#### To run:

$ ```sudo touchup```

#### Known Issues:
- The script can only be called using sudo
- The built-in OMZ updater is currenty not working
- Pacman doesn't show which packages are being updated. I highly recomend not using this on Arch.
- RedHat support will maybe be added in the future. For now only Debian, Arch & MacOS based systems are supported.
