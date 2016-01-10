# pulseaudio-equalizer
Updated PulseAudio Equalizer w/OpenSUSE Tumbleweed patches

# Building for Debian/Ubuntu
There is a simple `control` file included to build a `deb` file.

```bash
git clone https://github.com/ObsidianX/pulseaudio-equalizer pulseaudio-equalizer
dpkg-deb --build pulseaudio-equalizer
sudo dpkg -i pulseaudio-equalizer.deb
```
