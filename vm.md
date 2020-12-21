# Virtual Machines

I use VirtualBox to run various operating systems, including:
- [Debian](https://www.debian.org/)
- [Ubuntu](https://ubuntu.com/download)
- [Kali](https://www.kali.org/downloads/)
- [Fedora](https://getfedora.org/en/workstation/download/)
- [Qubes](https://www.qubes-os.org/downloads/)
- [NixOS](https://nixos.org/download.html#download-nixos)

Here is how I get set up:
1. [Download & install VirtualBox.](https://www.virtualbox.org/wiki/Downloads)
2. Download an installer image (e.g. [the Debian network install](https://www.debian.org/CD/netinst/)).
3. In VirtualBox (from now on), click New (or Machine > New... ⌘N).
4. I prefer expert mode, but guided mode works similarly.
5. I usually name my VM after the OS, and omit the version.
6. Select the type & version of the OS (e.g. Linux, Debian (64-bit)).
7. On my 16 GB machine, I choose 4-8 GB (4096-8192 MB) or more of memory.
8. I leave storage on the default option: "Create a virtual hard disk now"
9. I click create, then choose a little under 32 GB (31.27 GB to be exact).
10. I leave the file type as VDI & Dynamically allocated.
11. Click Settings (or Machine > Settings... ⌘S).
12. Under System > Processor, I choose 2 CPUs on my 2-core Intel Core i5.
13. IMPORTANT! (esp. for Fedora): Under display, I max the video memory to 128 MB.
14. Under storage, for the SATA storage I check Solid-state Drive (because I
have one).
15. Under storage, for the IDE drive I click the CD icon right of the menu, and
select "Choose a disk file..", then I choose the installer image I downloaded
in step 2.
16. Click the OK button to save the settings.
17. Click Start (or Machine > Start > Normal Start).
18. Install the guest operating system on the virtual machine.

