# systemd-pc-sleep-fix-for-hdmi-audio
Reactives HDMI Audio device after sleep the computer.

<b>Fix Bug 1252423 – HDMI Audio seen as 'unplugged' after Suspend</b>

Follow the steps:

1) - Download "fixhdmiaudio"

2) - As root move the file to "/lib/systemd/system-sleep/". Example:

<code>$ sudo cp fixhdmiaudio /lib/systemd/system-sleep/</code>

3) - Change the file permissions:

<code>$ sudo chmod 755 /lib/systemd/system-sleep/fixhdmiaudio</code>
