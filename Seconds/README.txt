

run: 
$ make
output:
make -C /lib/modules/4.4.0-87-generic/build M=/home/osc/final-src-osc10e/ch2 modules
make[1]: Entering directory '/usr/src/linux-headers-4.4.0-87-generic'
  CC [M]  /home/osc/final-src-osc10e/ch2/seconds.o
  Building modules, stage 2.
  MODPOST 1 modules
  CC      /home/osc/final-src-osc10e/ch2/seconds.mod.o
  LD [M]  /home/osc/final-src-osc10e/ch2/seconds.ko
make[1]: Leaving directory '/usr/src/linux-headers-4.4.0-87-generic'

next:
$ sudo insmod seconds.ko

next:
$ cat /proc/seconds
output:
Seconds: 4

to remove:
$ sudo rmmod seconds
