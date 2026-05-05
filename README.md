# virtualcabel-wfview
Add virtual cable for connect wfview to other software on ubuntu 26.04
Just copy 10-hamradio.conf to:

~/.config/pipewire/pipewire.conf.d/10-hamradio.conf

And run this command:

systemctl --user restart pipewire pipewire-pulse wireplumber
