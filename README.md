## Usage
`tty-clock [-iuvsScbtrahDBxn] [-C [0-7]] [-f format] [-d delay] [-a nsdelay] [-z scale] [-T tty]`

<table border="0" cellpadding="4">
<tr><td align="right"><code>-s</code></td><td>Show seconds</td></tr>
<tr><td align="right"><code>-S</code></td><td>Screensaver mode</td></tr>
<tr><td align="right"><code>-x</code></td><td>Show box</td></tr>
<tr><td align="right"><code>-c</code></td><td>Set the clock at the center of the terminal</td></tr>
<tr><td align="right"><code>-C [0-7]</code></td><td>Set the clock color</td></tr>
<tr><td align="right"><code>-b</code></td><td>Use bold colors</td></tr>
<tr><td align="right"><code>-t</code></td><td>Set the hour in 12h format</td></tr>
<tr><td align="right"><code>-u</code></td><td>Use UTC time</td></tr>
<tr><td align="right"><code>-T tty</code></td><td>Display the clock on the specified terminal</td></tr>
<tr><td align="right"><code>-r</code></td><td>Do rebound the clock</td></tr>
<tr><td align="right"><code>-f format</code></td><td>Set the date format</td></tr>
<tr><td align="right"><code>-n</code></td><td>Don't quit on keypress</td></tr>
<tr><td align="right"><code>-v</code></td><td>Show tty-clock version</td></tr>
<tr><td align="right"><code>-i</code></td><td>Show some info about tty-clock</td></tr>
<tr><td align="right"><code>-h</code></td><td>Show this page</td></tr>
<tr><td align="right"><code>-D</code></td><td>Hide date</td></tr>
<tr><td align="right"><code>-B</code></td><td>Enable blinking colon</td></tr>
<tr><td align="right"><code>-d delay</code></td><td>Set the delay between two redraws of the clock. Default 1s.</td></tr>
<tr><td align="right"><code>-a nsdelay</code></td><td>Additional delay between two redraws in nanoseconds. Default 0ns.</td></tr>
<tr><td align="right"><code>-z scale</code></td><td>Scale the clock UI (1-4). Default 1.</td></tr>
</table>

## Credits
- Scale factor option (`-z` flag) by [@author-handle](https://github.com/author-handle), originally submitted as [xorg62/tty-clock#120](https://github.com/xorg62/tty-clock/pull/120)
