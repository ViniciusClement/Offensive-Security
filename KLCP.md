# Kali Linux Certified Professional (KLCP)

# Filesystem Hierarchy Standard
```
/bin/: basic programs.
/boot/: Kali Linux kernel and other files required for its early boot process.
/dev/: device files.
    disk drives   (/dev/sda),
    partitions    (/dev/sda1),
    mice          (/dev/input/mouse0),
    keyboards     (/dev/input/event0),
    sound cards   (/dev/snd/*),
    serial ports  (/dev/ttyS*),
/etc/: configuration files.
/home/: user's personal files.
/lib/: basic libraries.
/media/: mount points for removable devices (CD/DVD-ROM, USB keys, and so on).
/mnt/: temporary mount point.
/opt/: extra applications provided by third parties.
/root/: administrator's (root's) personal files.
/run/: volatile runtime data that does not persist across reboots (not yet included in the FHS).
/sbin/: system programs.
/srv/: data used by servers hosted on this system.
/tmp/: temporary files (this directory is often emptied at boot).
/usr/: applications (this directory is further subdivided into bin, sbin, lib according to the same logic as in the root directory) Furthermore, /usr/share/ contains architecture-independent data. The /usr/local/ directory is meant to be used by the administrator for installing applications manually without overwriting files handled by the packaging system (dpkg).
/var/: variable data handled by services. This includes log files, queues, spools, and caches.
/proc/ and /sys/ are specific to the Linux kernel (and not part of the FHS). They are used by the kernel for exporting data to user space.

```
