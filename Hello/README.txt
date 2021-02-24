

run:
$ make

output:
osc@ubuntu:~/final-src-osc10e/ch2$ make
make -C /lib/modules/4.4.0-87-generic/build M=/home/osc/final-src-osc10e/ch2 modules
make[1]: Entering directory '/usr/src/linux-headers-4.4.0-87-generic'
  Building modules, stage 2.
  MODPOST 1 modules
make[1]: Leaving directory '/usr/src/linux-headers-4.4.0-87-generic'

next:
$ ./insrem.sh

output:
beginning script...

[ 1886.216790] /proc/hello created
[ 1886.216793] GOLDEN_RATIO_PRIME is: 11400862456688148481
[ 1886.216795] In proc_init(), Jiffies is: 4295363791 and HZ is: 250
[ 1886.222822] The gcd of 3,300 and 24 is: 12
[ 1886.222824] In proc_exit(), jiffies is: 4295363792
[ 1886.222825] /proc/hello removed

...end of script