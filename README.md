Building Putty-cyg-tray
=======================

    ./mkfiles.pl
    make -C windows -f Makefile.cyg putty.exe
    make -C windows/cthelper -f Makefile
    size windows/putty.exe windows/cthelper/cthelper.exe

Then you will need to copy windows/putty.exe and windows/cthelper/cthelper.exe to the same directory.

