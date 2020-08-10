<p align="center">
<img src="https://raw.githubusercontent.com/R-Teer/Costume-For-Mac/master/icon.png" width="128" height="128" title="Costume For Mac">
</p>

# Costume

### Express Theming For Mac
Themeing Software for Mac OS Catalina and Big Sur

#### About

Costume is a native themeing engine for Mac OS X Catalina and for the upcoming release Mac OS 11 Big Sur.

Costume relies on the modification of system resources stored within Mac OS, specifically the .car system appearance packages.

#### SIP 

On Catalina 
SIP must be disabled using

csrutil disable

SIP has changed dramatically in Big Sur and no longer allows booting from a live disk. Instead we are booted from a snapshot of the disk that prevents the tampering of system files.  

Steps to edit system files on Big Sur 

- Create a mount point for the live snapshot
- Make adjustments
- Create new snapshot to boot from
- Reboot







#### To Do

- [ ] Work with SIP enabled (currently requires SIP disabled)
- [x] Decompile .car files on Catalina 10.16.6
- [x] Edit System resources (Port of MILK theme has been completed)
- [x] Complile installer for replacing correct system resources


