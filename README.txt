README.TXT
2/17/2017
Michael Tang miytang
Calvin Yang cahyang
Georgios Karagiannis gekaragi
Roman Sodermans rsoderma

Included Files and Documents:
README.txt
DESIGN.pdf
sched_ule.c
kern_switch.c
kern_thread.c
syscalls.master
proc.h
runq.h

To build kernel, run the command:
make -j2 -DKERNFAST buildkernel KERNCONF=MYKERNEL
To install kernel, run the command:
make -j2 installkernel KERNCONF=MYKERNEL
where -j2 refers to the number of cores of your virtual machine.

Nice() and gift() calls usage explained in design document.

NOTE: We include the tag " TEAM WINNING " near all of our
additions wherever possible to make it easier to locate
and differentiate our code from the original kernel
