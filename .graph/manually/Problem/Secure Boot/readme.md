https://ask.fedoraproject.org/t/fedora-linux-kernel-update-breaks-nvidia-driver/21954

>With earlier releases of fedora the nvidia driver could only be activated with secure boot disabled. Is that the case here?
You can tell with dmesg | grep -iE 'nvidia|secure'
>
>Also, you can tell what nvidia driver is installed with dnf list installed akmod-nvidia. The current release is 510.60 for fedora 35 and will soon be updated to 510.68 after 36 is released and you upgrade.
>
>If you are still running the 470 driver then you need to know what nvidia card you have before updating to the latest since the nvidia upgrade from 470 to 495 and beyond dropped support for some of the earlier cards.

sch: https://www.google.com/search?q=fedora+nvidia+secure+boot
