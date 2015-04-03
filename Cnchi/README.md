# CNCHI TODO LIST

## v0.8 Release

### General
- [x] Fix download global index (num of packages to download / num of packages downloaded)
- [ ] In NOX, create a network setup by default (copy networkmanager settings to netctl)
- [ ] Add Enlightenment
- [ ] Add LXQT (still in AUR)

### Complete Test Install For Each Desktop

- [ ] Xfce
- [ ] Openbox
- [ ] MATE
- [ ] Cinnamon
- [ ] KDE
- [x] GNOME
- [x] NOX

## 0.9.x Development Cycle

### General:
 - [x] Check if we can remove subprocess calls to pythonian code
 - [ ] Encrypt home directory (needs testing)
 - [x] Revamp the UI with a minimal, flat design.
 - [x] Fix empty space at the bottom of some screens.
 - [x] Get aria2 working in download.py so we have more control over any failures.
 - [ ] Create a symbolic version of our logo icon for use in GNOME (GNOMENU)
 - [x] New XML layout
 - [x] Window size fluctuations.
 - [ ] Add welcome app

### Bootloader Setup
 - [ ] Fix and reactivate UEFI bootloader install on GPT drives.

### Automatic Install:
 - [ ] Allow GPT (instead of MBR) installation in UEFI and non UEFI systems (needs testing)
 - [ ] Allow partion type and cipher selection

### Advanced Install:
 - [ ] If you play with the partitioner (create partition, delete it, create it again, delete it again...) in the end it gets confused.
 - [ ] Use [blivet](https://dlehman.fedorapeople.org/blivet-docs/) instead of pyparted
 - [ ] Add LVM support (create / delete / edit)
 - [ ] Add LUKS support (create / delete / cipher selection / edit) (partially done)
 - [ ] Add btrfs subvolume support
 - [ ] Add RAID support
 - [ ] Add ZFS support
 - [ ] Think about (if necessary) the use of /boot and /boot/efi in UEFI systems [#186](https://github.com/Antergos/Cnchi/issues/186)

### Slides screen:
 - [x] Redo ALL slides
 - [ ] Remove popup (install completed) and add a message inside the slides screen instead.
 - [ ] Use WebKit2

### Alongside Install:
 - [ ] Finish this option (wait for Blivet)

### Enlightenment Desktop:
 - [ ] Enable connman in process.py
 - [ ] Set Antergos wallpaper
 - [ ] Add music player
 - [ ] Check that .config directory is not owned by root (test again)
 - [ ] Set GTK Theme : gtk-theme-e17gtk to match E19 default theme.
 - [ ] Set Numix Icons
 - [ ] Change GTK Font (from Cantarell 11 to Sans 10, for instance)
 - [ ] Change Terminology font (default one is too small!)
 
And much more... (see [issues](https://github.com/Antergos/Cnchi/issues?milestone=4&page=1&state=open) in github)
