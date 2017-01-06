FROM base/archlinux
RUN pacman -Sy archlinux-keyring
RUN pacman-key --refresh-keys
RUN pacman -Syu --noconfirm --force inkscape
CMD /usr/bin/inkscape
