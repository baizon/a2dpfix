# a2dpfix
This is a fix of the High Fidelity Playback A2DP Sink (unavailable) for my Sony WH-1000XM2 headphones.<br>
Big thanks to Diego Fernandez for the code.

## Install
1. Edit the paths within `a2dp-fix-wrapper` and `80-bt-headset.rules`
2. Copy `80-bt-headset.rules` to `/etc/udev/rules.d/`

## Links
Source: https://github.com/aiguofer/dotfiles <br>
Link: https://gitlab.freedesktop.org/pulseaudio/pulseaudio/issues/525
