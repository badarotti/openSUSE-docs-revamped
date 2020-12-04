# New User Guide

The goal of the documentation on this site is to get your system up and running as fast as possible with minimum configuration. Like with any operating system you need to make a couple of decisions in relations of your current hardware and what kind of technologies you want to use. Here we will explain the essentials for you to start your installation.

!!! note
    You can install a system that you can use as a Desktop or a Server. This section of the documentation focuses on setting up a desktop system.

   
## Pre-isntall considerations
   
### Distributions

A distribution is a version of the openSUSE operating system. It contains the  installer, the operating system and the programs necessary to make your computer operational. 

When you go to [get.opensuse.com](https://get.opensuse.org/) to download openSUSE you will find that there are two main distributions. Leap (stable) and Tumbleweed (Rolling).

Pre-Install > [The distribution Guide](distribution.md)

### Installation Media

When you download the version of openSUSE you wish to use, you will download an single image file with a (.iso) extension. You write the ISO image file to a USB flash drive, a blank DVD or CD to create the **Installation Media** that includes the installer and the applications that will make your computer ready for everyday use. Simply boot you computer from the Installation Media to begin the installation process.

Pre-Install > [Installation Media Guide](install_media.md)

### Desktop Environments

Linux gives you lots of choices including the various DE (Desktop Environment) which is the GUI of the operating system. If you're a new Linux user we recommend using the default KDE DE, it is very slick, powerful yet easy to use. If you feel more adventurous you can change the DE during the installation or anytime after you install openSUSE.

Pre-install > [Desktop Environments Guide](desktop_environment.md)

### Drive Partitioning

If you are installing openSUSEon a new drive or you want the openSUSE installer to write over your whole drive deleting everything on it, then the installer will give you that option during installation and you won't have to do any preparations before hand.

In case you you want to preserve an existing partitions and the data it contains, or if you want to dual boot openSUSE with another operating system like Windows; you will find useful tips and tricks in the following guides to achieve your goal safely.

Pre-Install > [Partitioning Guide](drive_partition.md)  
Pre-install > [Dual Booting Guide](dual_boot.md)

### Disk Encryption

Linux has the technology to encrypt your drive for security reasons. If this technology is enabled you will be asked for your passphrase every time you boot your computer. It is recommended to enable disk encryption on laptops as well as desktop computers that are placed in environments that you do not completely control.

Pre-Install > [Disk Encryptio Guide](disk_encryption.md)

### Snapshots & Btrfs

openSUSE uses Btrfs file system and it's snapshot technologies to automatically restore the operating system to a previous known working state in case something goes wrong with an update or upgrade. The technology is automatic and the restoration can be done using the GUI or via the command line interface. 

Pre-install > [Snapshots and Btrfs Guide](btrfs.md)
