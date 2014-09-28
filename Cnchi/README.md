# CNCHI TODO LIST

## v0.8 Release

### General Blockers
- [ ] Port v0.8 changes to CLI
- [ ] Fix download global index (num of packages to download / num of packages downloaded)
- [ ] In NOX, create a network setup by default (copy networkmanager settings to netctl)
- [ ] Add Enlightenment and LXQT

### Complete Test Install For Each Desktop

- [ ] Xfce
- [ ] Enlightenment
- [ ] Lxqt
- [ ] Openbox
- [ ] MATE
- [ ] Cinnamon
- [ ] KDE
- [ ] GNOME
- [ ] NOX

## v0.8 Development Cycle

### General:
 - [ ] Check if we can remove subprocess calls to pythonian code
 - [ ] Encrypt home directory (needs testing)
 - [ ] Revamp the UI with a minimal, flat design.
 - [ ] Fix empty space at the bottom of some screens.
 - [ ] Get aria2 working in download.py so we have more control over any failures.
 - [ ] Create a symbolic version of our logo icon for use in GNOME (GNOMENU)
 - [ ] Finish wireless screen (this way network-manager applet won't be necessary)
 karasu: I do not understand this. Wireless screen uses network-manager, so it won't solve anything :(
 - [ ] New XML layout
 - [ ] Window size fluctuations.

### Bootloader Setup
 - [ ] Fix and reactivate UEFI bootloader install on GPT drives.

### Automatic Install:
 - [ ] Allow GPT (instead of MBR) installation in UEFI systems
 - [ ] Allow partion type and cipher selection

### Advanced Install:
 - [ ] If you play with the partitioner (create partition, delete it, create it again, delete it again...) in the end it gets confused.
 - [ ] Use [blivet](https://dlehman.fedorapeople.org/blivet-docs/) instead of pyparted
 - [ ] Add LVM support (create / delete / edit)
 - [ ] Add LUKS support (create / delete / cipher selection / edit)
 - [ ] Add btrfs subvolume support
 - [ ] Add RAID support
 - [ ] Add ZFS support
 - [ ] Think about (if necessary) the use of /boot and /boot/efi in UEFI systems [#186](https://github.com/Antergos/Cnchi/issues/186)

### Slides screen:
 - [ ] Redo ALL slides
 - [ ] Remove popup (install completed) and add a message inside the slides screen instead.

### Alongside Install:
 - [ ] Finish this option. Doesn't work as it is (in fact, is a mess, should be rewritten).

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
