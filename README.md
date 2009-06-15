Building Putty-cyg-tray
=======================

    make -C windows -f Makefile.cyg putty.exe
    make -C windows/cthelper
    size windows/putty.exe windows/cthelper/cthelper.exe

