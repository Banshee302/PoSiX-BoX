PoSiX-BoX Linux Emulator

For interacting with the Emulator via C/C++ you can use pbox32/headers for the emulator headers, this is mainly used for communicating with the Emulator to carry out Operations above the Emulated User space mode.

pbox32/utils holds all the utilities that can be used to debug the emulator.

pbox32/root is the root directory for the Emulator, which holds crucial headers for the emulator.

pbox32/systrace are syscall/crash logs, with system side being logged as SYS: which is the System in the Emulator, the emulator side being logged as EMUL:

systrace files have a timestamp at the top, e.g:

== TIME: <date>@<time of log in 24 hour time> ==