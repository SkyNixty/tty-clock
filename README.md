## Usage 
tty-clock [-iuvsScbtrahDBxn] [-C [0-7]] [-f format] [-d delay] [-a nsdelay] [-z scale] [-T tty]<br>
    -s            Show seconds<br>
    -S            Screensaver mode<br>
    -x            Show box<br>
    -c            Set the clock at the center of the terminal<br>
    -C [0-7]      Set the clock color<br>
    -b            Use bold colors<br>
    -t            Set the hour in 12h format<br>
    -u            Use UTC time<br>
    -T tty        Display the clock on the specified terminal<br>
    -r            Do rebound the clock<br>
    -f format     Set the date format<br>
    -n            Don't quit on keypress<br>
    -v            Show tty-clock version<br>
    -i            Show some info about tty-clock<br>
    -h            Show this page<br>
    -D            Hide date<br>
    -B            Enable blinking colon<br>
    -d delay      Set the delay between two redraws of the clock. Default 1s.<br>
    -a nsdelay    Additional delay between two redraws in nanoseconds. Default 0ns.<br>
    -z scale      Scale the clock UI (1-4). Default 1.<br>

## Credits
- Scale factor option (`-z` flag) by [@author-handle](https://github.com/author-handle), originally submitted as [xorg62/tty-clock#120](https://github.com/xorg62/tty-clock/pull/120)
