Building Putty-cyg-tray
=======================

I modified the `mkfiles.pl` script to take an argument of either `-d` or `--debug`
if you want to compile the program with debugging symbols enabled.

    ./mkfiles.pl
    make -C windows -f Makefile.cyg putty.exe
    make -C windows/cthelper -f Makefile
    size windows/putty.exe windows/cthelper/cthelper.exe

Then you will need to copy windows/putty.exe and windows/cthelper/cthelper.exe
to the same directory.

