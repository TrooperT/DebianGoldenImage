# Debian 9 Golden Image
---

### Subject

Provide repeatable step by step instructions to build a ready to deploy Debian 9 system image in OVA/OVF formats.

---
### Prerequisites
You will need:
 * A working Debian 9 Linux VM to be used as the "build station" with an additional 2 disks:
   * 25GB: for building the golden rootfs
   * 75GB: for scratchdisk, working with disk images, etc.

   * and the following packages installed:
     * debootstrap
     * lvm2
     * ssh-import-id
---
### Instructions
