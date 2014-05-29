# CNCHI TODO LIST

## v0.6 Release Blockers

### General
- [x] Port v0.6 changes to CLI
- [x] Choose a progress bar color/design.
- [x] Discuss/Decide on adding Dash-to-Dock and GNO-MENU extensions to GNOME.
- [x] Keyboard Screen - Fix image so it fits without being cut off.
- [x] Feature Screen - Entire window shrinks in size causing horizontal scroll bars to show.
- [x] Welcome Screen - Make the progressbar stay hidden. It wasn't working on the last attempt.
- [x] Window size fluctuations.
- [x] Disable Razor-QT
- [x] KDE config corrections.

### Complete Test Install For Each Desktop

#### @faidoc

- [ ] Xfce
- [ ] Openbox
- [x] MATE
- [x] Cinnamon
- [ ] KDE
- [x] GNOME
- [x] NOX

#### @karasu

- [ ] Xfce
- [ ] Openbox
- [ ] MATE
- [ ] Cinnamon
- [x] KDE
- [x] GNOME
- [ ] NOX (network does not work out-of-the-box, must setup netctl manually)

#### @lots0logs

- [ ] Xfce
- [ ] Openbox
- [ ] MATE
- [x] Cinnamon
- [ ] KDE
- [x] GNOME
- [x] NOX


## v0.8 Development Cycle

### General:
 - [ ] Check if we can remove subprocess calls to pythonian code
 - [ ] Encrypt home directory (needs testing)
 - [ ] Revamp the UI with a minimal, flat design.
 - [ ] Fix empty space at the bottom of some screens.
 - [ ] Get aria2 working in download.py so we have more control over any failures.
 - [ ] Create a symbolic version of our logo icon for use in GNOME (GNOMENU)
 - [ ] Finish wireless screen (this way network-manager applet won't be necessary)
 - [ ] New XML layout
 - [ ] Add Enlightenment and LXDE

### Bootloader Setup
 - [ ] Fix and reactivate UEFI bootloader install on GPT drives.

### Automatic Install:
 - [ ] Allow GPT (instead of MBR) installation in UEFI systems
 - [ ] Allow partion type and cipher selection

### Advanced Install:
 - [ ] If you play with the partitioner (create partition, delete it, create it
   again, delete it again...) in the end it gets confused.
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
 - [ ] Finish this option. Doesn't work as it is.

 
And much more... (see [issues](https://github.com/Antergos/Cnchi/issues?milestone=4&page=1&state=open) in github)
