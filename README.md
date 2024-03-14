# NACL (SALT) The OPUS-CBCS System Assembler, Lister, Tester

   Usage:      NACL [options] ctlfile

   Options:    /TERSE .... don't display warning messages
               /LIST  .... generate a parm file report
               /VERIFY.... system checkout
               /INFO  .... display `in progress' messages

   Example:    Assemble BBS.CTL, generate a report, and checkout system...
                  NACL /LIST /VERIFY bbs

   Notes:      For a complete checkout, use /LIST and /VERIFY together.
               The output for /LIST and /VERIFY goes to the standard output
               device.  You can redirect this to a disk file or to a printer.
               See your DOS reference manual for details on redirecting
               standard output.
