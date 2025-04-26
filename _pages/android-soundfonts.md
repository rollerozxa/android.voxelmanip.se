---
title: Android Soundfonts
---

When playing back MIDI music using Android's system audio playback functionality, a built-in soundfont is used. This gives Android games that make use of a soundtrack in MIDI format a specific sound to them that cannot be replicated elsewhere without the right soundfont set.

The soundfonts used is available for download on the [Internet Archive](https://archive.org/details/android-midi-soundfonts). They come in the `.sf2` format and there are four different types of soundfonts:

- [`ANDROID_1.sf2`](https://archive.org/download/android-midi-soundfonts/ANDROID_1.sf2)
- [`ANDROID_2.sf2`](https://archive.org/download/android-midi-soundfonts/ANDROID_2.sf2)
- [`ANDROID_3.sf2`](https://archive.org/download/android-midi-soundfonts/ANDROID_3.sf2)
- [`ANDROID_4.sf2`](https://archive.org/download/android-midi-soundfonts/ANDROID_4.sf2)

These files were sourced from somewhere in the AOSP file tree, which I cannot remember anymore.

To play MIDI music with a specific soundfont, you may use VLC Media Player which integrates MIDI playback using FluidSynth. You can find the setting to change the soundfont used for playback in VLC by going to Tools -> Settings -> All Settings (bottom left radio button) -> Input / Codecs -> Audio codecs -> FluidSynth -> SoundFont-file.
