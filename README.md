# linux-0.01-1
build linux 0.01 on x86_64, use gcc 4.4 (check compile.txt)
 
unzip hd_oldlinux.img.zip

./make

./../qemu-2.5.0/i386-softmmu/qemu-system-i386 -hdb hd_oldlinux.img -fda Image -boot a
