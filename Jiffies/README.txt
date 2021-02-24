

run:
$ make
output:
make -C /lib/modules/4.4.0-87-generic/build M=/home/osc/final-src-osc10e/ch2 modules
make[1]: Entering directory '/usr/src/linux-headers-4.4.0-87-generic'
  CC [M]  /home/osc/final-src-osc10e/ch2/jiffies.o
  Building modules, stage 2.
  MODPOST 1 modules
  LD [M]  /home/osc/final-src-osc10e/ch2/jiffies.ko
make[1]: Leaving directory '/usr/src/linux-headers-4.4.0-87-generic'

next:
$ sudo insmod jiffies.ko

next:
$ cat /proc/jiffies
output:
Jiffies: 4295526972

to remove:
sudo rmmod jiffies