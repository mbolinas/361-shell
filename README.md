# CISC361: Operating Systems - custom shell

Created by Brian Phillips and Marc Bolinas

IMPORTANT & NEW (for Professor or TA):
watchuser implementation can be found under watchuser.c
watchmail implementation can be found under watchmail.c
Both watchmail and watchuser are used in sh.c through #include statements
     (#include "watchmail.c" and #include "watchuser.c"
The functions the watchuser and watchmail threads run is found in base_commands.c
    (functions are watchmail() and watchuser())
Redirection, noclobber, and inter-process communication are all found in sh.c



Old news:
type 'make' when in the directory to compile to file called 'shell'

type "exit" to quit