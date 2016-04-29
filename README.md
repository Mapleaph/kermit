# kermit
This file is used by the command line tool C-Kermit in the Linux environment.
Move the kermrc file to the home dir of the current user, and rename it to .kermrc (hidden file).

## Simple tutorial of C-Kermit

### Installation

``` bash
$ sudo apt-get install ckermit
```

### How to use?

1. First check the actual serial port name, if it is not /dev/ttyUSB0, then you should change it from ~/.kermrc file
2. $ sudo ckermit
3. press c to connect to the device, and the display will switch to the terminal mode.
4. press Ctrl+\ c to switch the mode back to ckermit command prompt.

## Attention
The commands defined in the .kermrc file are used for the purpose of Ti AM335x Development Board.
