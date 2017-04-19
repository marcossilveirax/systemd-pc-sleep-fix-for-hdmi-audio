# systemd-pc-sleep-fix-for-hdmi-audio
Reactives HDMI Audio device after sleep the computer.

Follow the steps:

1 - Download "fixhdmiaudio"

2 - As root move the file to "/lib/systemd/system-sleep/". Example:

$ sudo cp fixhdmiaudio /lib/systemd/system-sleep/
