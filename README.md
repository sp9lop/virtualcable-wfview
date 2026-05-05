Add virtual cable can connect wfview to other software on ubuntu 26.04<br>
Just copy 10-hamradio.conf to:

~/.config/pipewire/pipewire.conf.d/10-hamradio.conf

And run this command:

<code>systemctl --user restart pipewire pipewire-pulse wireplumber</code>

This is tested on IC-705 and WSJT-X 3.0.0 on ubuntu 26.04
