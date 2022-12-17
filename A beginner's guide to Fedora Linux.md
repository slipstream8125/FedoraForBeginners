## Pros
- Fedora is a bleeding edge distro like Arch. This means that it has the latest kernel and software is available in the distro.
- However, unlike Arch, Fedora tends to be on the more stable side which makes it more viable as a daily driver.
- This can be particularly useful in the case of newer devices like laptops which often have newer or proprietary drivers and end up needing newer kernels.
- Fedora comes with GNOME as its default DE which is beginner-friendly. However, if the user doesn't like GNOME, they can always install Fedora with their preferred DE using Fedora Spins
 (https://spins.fedoraproject.org/).

## Cons
- DNF(Dandified Yum), the package manager used in Fedora is slower at refreshing its repositories than APT or Pacman
- There is a bit of a learning curve on Fedora for the users who have previously used Ubuntu-based distros due to some differences in the inbuilt commands
- The situation with the NVIDIA drivers is a bit more complicated in Fedora than Ubuntu due to the presence of more than one repos for providing those drivers

# Personal thoughts and Experience using Fedora
## Reason for Using Fedora
The reason I started using Fedora was because my laptop(ROG Zephyrus G14) had better support for its drivers and asusctl(a module to access power profiles,keyboard led,etc in Linux) had better support for Fedora than Ubuntu and Pop!\_OS.

# Installation Procedure
- Download Fedora from https://getfedora.org/.
- If you want to use any other DE than GNOME, download Fedora with your favourite DE from https://getfedora.org/.
- Write the ISO image to a USB drive using a software like Rufus(if you are on WIndows) or BalenaEtcher(works on Mac,Windows and Linux)
- Boot into the BIOS and disable secure boot
- Select your USB drive as the device to boot into
- You can also choose to test Fedora before installing it
![ScreenShot](/Images/file2.png)

- Click on Install Fedora when you want to install it
![ScreenShot](/Images/file1.png)
- Follow the instructions given in the software and install Fedora
![ScreenShot](/Images/file3.png)
