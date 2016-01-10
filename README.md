# pulseaudio-equalizer
Updated PulseAudio Equalizer w/OpenSUSE Tumbleweed patches

# Building for Debian/Ubuntu
There is a simple `control` file included to build a `deb` file.

```bash
git clone https://github.com/ObsidianX/pulseaudio-equalizer pulseaudio-equalizer
dpkg-deb --build pulseaudio-equalizer
sudo dpkg -i pulseaudio-equalizer.deb
```

Prebuilt available under Releases: [2.7.0.2](https://github.com/ObsidianX/pulseaudio-equalizer/releases/download/v2.7.0.2/pulseaudio-equalizer_2.7.0.2.deb "2.7.0.2")
