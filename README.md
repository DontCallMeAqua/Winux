# uWinux
The extremely light-weight Windows OS, powered entirely by Linux.
By Aqua/Aquarius/Aquarirus/DontCallMeAqua

uWinux (ju-wɪn-ʌks) Windows rewritten with Linux. The Operating System can run Windows executables, install Windows programs, run most Windows Essential programs and do everything else Linux-wise.

# uWinux for SBCs
uWinux for Single Board Computers (SBCs).

uWinux for SBCs is compatable with all SBCs, but is slightly different from uWinux as it cannot run Windows executables on it's own and relies on Wine for them.

Pros:
- Smoother
- Requires less RAM
- Requires less storage space
- Image under 200MB
- Uses GNOME

Cons:
- No Windows CMD
- No lintarna
- Doesn't run in VMs

# qWinux
uWinux for Touchscreen Devices.

qWinux (qe-wɪn-ʌks) comes in four forms:
- qWinux8
- qWinux10
- qWinuxA8
- qWinuxA10

qWinux8 is uWinux with a blocky Windows 8-like touchscreen interface (aka Start menu)

qWinux10 is uWinux with the Windows 10 Tablet Mode interface.

qWinixA8 is qWinux8 for ARMv7, ARMv8, ARMv9 and all other ARM devices (excluding smartphones and tablets).

qWinuxA10 is qWinux10 for ARMv7, ARMv8, ARMv9 and all other ARM devices (excluding smartphones and tablets).

# hWinux and sWinux
Headless uWinux OSs

# hWinux
The headless varient of uWinux.

The entire operating system consists of three key sections:
- Windows CMD/MS-DOS
- Debian Terminal
- Terminal Store

To switch between Terminals, run `sudo tswitch <Terminal-Name-Goes-Here>`.
To switch to a Linux terminal from CMD, run `cd <drive>:\lin | run <Terminal-Name-Goes-Here>.ter`
To switch to CMD from a Linux terminal, run `sudo su | cd root | ./cmd.exe`
To install more Terminals, you need to use the Terminal Store.
First, run `cd terstore | sudo ./terstore.sh` to open the Store.
Second, run `sudo ps ts apt-get install <Terminal-Name-Goes-Here>` to install a Terminal.
Third, exit the Store by running `sudo ps ts exit`.
Finally, run the terminal with `sudo su | cd root/lin | run <Terminal-Name-Goes-Here>.ter`.

#sWinux
uWinux for Servers.

sWinux is hWinux with server features implemented. (like Ubuntu Server)
