# Unix Filesystem Directories

Unix uses the separator "/", whereas Windows uses "\".

Unix is case sensitive, Windows is not. Macs can be either.

Single user mode allows a system administrator to perform maintenance on the system.

Several top level directories have been unified under /usr, including:
- /bin
- /lib
- /sbin

| Directory        | Description                                                              |
| ---------------- | ------------------------------------------------------------------------ |
| /                | The root directory                                                       |
| /bin             | Binaries, a.k.a. programs (e.g. ls, cat, ...)                            |
| /boot            | Everything needed to boot, such as a bootloader                          |
| /dev             | Virtual files for each device                                            |
| /etc             | Configuration files                                                      |
| /home            | User directories, for personal files                                     |
| /home/me         | An example user directory                                                |
| /home/me/.local  | Locally installed programs for this user                                 |
| /home/me/.config | Configuration for locally installed user programs                        |
| /lib             | Libraries                                                                |
| /media           | Disks mounted automatically, if it exists                                |
| /mnt             | Disks mounted (manually, if /media exists)                               |
| /opt             | Self contained, user installed software                                  |
| /proc            | A virtual filesystem providing information about processes               |
| /proc/cpuinfo    | Information about the CPU                                                |
| /proc/uptime     | How long the system has been running for                                 |
| /root            | The root user's home directory                                           |
| /run             | Runtime information for early boot programs                              |
| /sbin            | System binaries, required for single user mode, along with /bin          |
| /snap            | Snap packages are self contained Ubuntu applications                     |
| /srv             | Service data goes here, for example Web server document roots            |
| /sys             | The system folder is a virtual filesytem for interacting with the kernel |
| /tmp             | Temporary files, possibly emptied upon reboot                            |
| /usr             | Userspace applications                                                   |
| /usr/bin         | See /bin                                                                 |
| /usr/lib         | See /lib                                                                 |
| /usr/sbin        | See /sbin                                                                |
| /usr/share       | Large applications (so you can link to a shared network drive, maybe)    |
| /usr/src         | Source code, such as the kernel source and header files                  |
| /usr/local       | Locally installed applications                                           |
| /usr/local/bin   | Local binaries                                                           |
| /usr/local/lib   | Local libraries                                                          |
| /usr/local/src   | Local source code                                                        |
| /var             | Files expected to grow in size                                           |
| /var/log         | Log files                                                                |
| /var/mail        | Email databases                                                          |
| /var/spool       | Printer queues                                                           |
